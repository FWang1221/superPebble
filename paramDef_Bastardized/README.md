This folder should also go into the Game Directory. Convert Paramdef XMLs to Lua tables using the HTML file in /shittyconverter. Load the paramDef tables through:

    pcall(loadfile("paramDef_Bastardized\\CreateOffsetTable.lua"))

The processed tables look as follows:

    AtkParamPC_Offsets = {
        ["paramType"] = PARAM_AtkParam_Pc,
        ["sizeOf"] = 456, -- from libEr
        ["offsetTable"] = calculateOffset(AtkParamPreprocessedTable)
    }
    AtkParamNPC_Offsets = {
        ["paramType"] = PARAM_AtkParam_Npc,
        ["sizeOf"] = 456, -- from libEr
        ["offsetTable"] = calculateOffset(AtkParamPreprocessedTable)
    }
    BehaviorParamPC_Offsets = {
        ["paramType"] = PARAM_BehaviorParam_PC,
        ["sizeOf"] = 32, -- from libEr
        ["offsetTable"] = calculateOffset(BehaviorParamPreprocessedTable)
    }
    BehaviorParamNPC_Offsets = {
        ["paramType"] = PARAM_BehaviorParam,
        ["sizeOf"] = 32, -- from libEr
        ["offsetTable"] = calculateOffset(BehaviorParamPreprocessedTable)
    }
    BuddyParam_Offsets = {
        ["paramType"] = PARAM_BuddyParam,
        ["sizeOf"] = 160, -- from libEr
        ["offsetTable"] = calculateOffset(BuddyParamPreprocessedTable)
    }
    BuddyStoneParam_Offsets = {
        ["paramType"] = PARAM_BuddyStoneParam,
        ["sizeOf"] = 64, -- from libEr
        ["offsetTable"] = calculateOffset(BuddyStoneParamPreprocessedTable)
    }
    BulletParam_Offsets = {
        ["paramType"] = PARAM_Bullet,
        ["sizeOf"] = 272, -- from libEr
        ["offsetTable"] = calculateOffset(BulletParamPreprocessedTable)
    }
    CalcCorrectGraphParam_Offsets = {
        ["paramType"] = PARAM_CalcCorrectGraph,
        ["sizeOf"] = 80, -- from libEr
        ["offsetTable"] = calculateOffset(CalcCorrectGraphParamPreprocessedTable)
    }
    CharaInitParam_Offsets = {
        ["paramType"] = PARAM_CharaInitParam,
        ["sizeOf"] = 320, -- from libEr
        ["offsetTable"] = calculateOffset(CharaInitParamPreprocessedTable)
    }
    EquipParamAccessory_Offsets = {
        ["paramType"] = PARAM_EquipParamAccessory,
        ["sizeOf"] = 96, -- from libEr
        ["offsetTable"] = calculateOffset(EquipParamAccessoryPreprocessedTable)
    }
    EquipParamCustomWeapon_Offsets = {
        ["paramType"] = PARAM_EquipParamCustomWeapon,
        ["sizeOf"] = 16, -- from libEr
        ["offsetTable"] = calculateOffset(EquipParamCustomWeaponPreprocessedTable)
    }
    EquipParamGem_Offsets = {
        ["paramType"] = PARAM_EquipParamGem,
        ["sizeOf"] = 96, -- from libEr
        ["offsetTable"] = calculateOffset(EquipParamGemPreprocessedTable)
    }
    EquipParamGoods_Offsets = {
        ["paramType"] = PARAM_EquipParamGoods,
        ["sizeOf"] = 176, -- from libEr
        ["offsetTable"] = calculateOffset(EquipParamGoodsPreprocessedTable)
    }
    EquipParamProtector_Offsets = {
        ["paramType"] = PARAM_EquipParamProtector,
        ["sizeOf"] = 416, -- from libEr
        ["offsetTable"] = calculateOffset(EquipParamProtectorPreprocessedTable)
    }
    EquipParamWeapon_Offsets = {
        ["paramType"] = PARAM_EquipParamWeapon,
        ["sizeOf"] = 664, -- from libEr
        ["offsetTable"] = calculateOffset(EquipParamWeaponPreprocessedTable)
    }
    LockCamParam_Offsets = {
        ["paramType"] = PARAM_LockCamParam,
        ["sizeOf"] = 128, -- from libEr
        ["offsetTable"] = calculateOffset(LockCamParamPreprocessedTable)
    }
    MagicParam_Offsets = {
        ["paramType"] = PARAM_Magic,
        ["sizeOf"] = 168, -- from libEr
        ["offsetTable"] = calculateOffset(MagicParamPreprocessedTable)
    }
    NpcParam_Offsets = {
        ["paramType"] = PARAM_NpcParam,
        ["sizeOf"] = 736, -- from libEr
        ["offsetTable"] = calculateOffset(NpcParamPreprocessedTable)
    }
    NpcThinkParam_Offsets = {
        ["paramType"] = PARAM_NpcThinkParam,
        ["sizeOf"] = 228, -- from libEr
        ["offsetTable"] = calculateOffset(NpcThinkParamPreprocessedTable)
    }
    SpEffectParam_Offsets = {
        ["paramType"] = PARAM_SpEffectParam,
        ["sizeOf"] = 912, -- from libEr
        ["offsetTable"] = calculateOffset(SpEffectParamPreprocessedTable)
    }
    SpEffectVfxParam_Offsets = {
        ["paramType"] = PARAM_SpEffectVfxParam,
        ["sizeOf"] = 164, -- from libEr
        ["offsetTable"] = calculateOffset(SpEffectVfxParamPreprocessedTable)
    }
    SwordArtsParam_Offsets = {
        ["paramType"] = PARAM_SwordArtsParam,
        ["sizeOf"] = 32, -- from libEr
        ["offsetTable"] = calculateOffset(SwordArtsParamPreprocessedTable)
    }
