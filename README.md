These files should all go into the Game Directory.

The Game Directory is commonly found in: C:\Program Files (x86)\Steam\steamapps\common\ELDEN RING\Game

Or otherwise, it is where your eldenring.exe application is stored.

MinHKSLib Features:

    {"abort", &Labort}, // abort minhkslib
    {"puts", &Lputs}, // print line
    {"curl", &Lcurl}, // make GET request
    {"curlPost", &LcurlPost}, // make POST request
    {"minimizeConsole", &LminimizeConsole}, // minimize console
    {"bringConsoleToFront", &LbringConsoleToFront}, // bring console to front of screen with dimensions and coords
    {"readConsoleLine", &LreadConsoleLine}, // take in stdin from player from console
    {"clearConsole", &LclearConsole}, // (failed) clears text content on console
    {"createOverlay", &LcreateOverlay}, // displays text at a coordinate. doesn't show up on screen recorders due to api being too low-level. swap the project to cpp and use directx
    {"displayImage", &LdisplayBMPImage}, // (failed) displays a BMP image at a coordinate. doesn't work and probably isn't the best. as stated earlier, swap to cpp and use directx
    {"startWebService", &LstartWebService}, // starts a web service that listens to port 8888 (2 GET methods: "/mictest/<yourstuffhere>" <- that sets the static string to whatever <yourstuffhere> was. "/viewFile/" <- sends over a file located in the Game Directory /eldenWeb.)
    {"stopWebService", &LstopWebService}, // stops the web service
    {"getStaticString", &LgetStaticString}, // pushes the static string (stored by the webservice's "/mictest/<yourstuffhere>" GET method (yes yes it's a GET method not a POST method))
    {"resetStaticString", &LresetStaticString}, // resets the static string back to default, should be called upon consumption of the string. The "REST API" is entirely in Lua.

