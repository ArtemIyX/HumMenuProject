# Project example for Menu Plugin
![menu](https://github.com/user-attachments/assets/94d82308-0597-445b-8e3d-938d1c4ff296)
![server](https://github.com/user-attachments/assets/6b34b6cf-a4c7-4287-b798-561802ecadf8)

## Asset Manager
```
+PrimaryAssetTypesToScan=(PrimaryAssetType="TextProperties",AssetBaseClass="/Script/HumMenuPlugin.TextPropertiesDataAsset",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets/TextStyles")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
+PrimaryAssetTypesToScan=(PrimaryAssetType="ButtonProperties",AssetBaseClass="/Script/HumMenuPlugin.ButtonPropertiesDataAsset",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets/ButtonProperties")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
+PrimaryAssetTypesToScan=(PrimaryAssetType="WidgetsProperties",AssetBaseClass="/Script/HumMenuPlugin.WidgetsPropertiesDataAsset",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
+PrimaryAssetTypesToScan=(PrimaryAssetType="ButtonAction",AssetBaseClass="/Script/HumMenuPlugin.ButtonActionDataAsset",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets/ButtonActionDescribe")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
+PrimaryAssetTypesToScan=(PrimaryAssetType="ScrollSettings",AssetBaseClass="/Script/HumMenuPlugin.MenuScrollsSettings",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
+PrimaryAssetTypesToScan=(PrimaryAssetType="TextBoxProperties",AssetBaseClass="/Script/HumMenuPlugin.TextBoxPropertiesDataAsset",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
+PrimaryAssetTypesToScan=(PrimaryAssetType="CheckBoxProperties",AssetBaseClass="/Script/HumMenuPlugin.CheckBoxPropertiesDataAsset",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
+PrimaryAssetTypesToScan=(PrimaryAssetType="SliderProperties",AssetBaseClass="/Script/HumMenuPlugin.SliderPropertiesDataAsset",bHasBlueprintClasses=False,bIsEditorOnly=False,Directories=((Path="/HumMenuPlugin/DataAssets")),SpecificAssets=,Rules=(Priority=-1,ChunkId=-1,bApplyRecursively=True,CookRule=AlwaysCook))
```

## Blueprint Subsystems
- BPS_ServerSaver
![subsystems](https://github.com/user-attachments/assets/17608cb9-b231-4df9-8108-3c69f4949d1e)

## Dependecies
- [MenuPlugin (dev branch)](https://github.com/ArtemIyX/HumMenuPlugin)
- [AdvancedAsset](https://github.com/ArtemIyX/AdvancedAssetUnreal)
- [BlueprintSubsystems](https://github.com/ArtemIyX/BlueprintSubsystemsUnreal)
- [DataSerializer](https://github.com/ArtemIyX/DataSerializerUnreal)
- [EasySettings](https://github.com/ArtemIyX/EasySettingsUnreal)
