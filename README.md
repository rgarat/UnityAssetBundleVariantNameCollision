# UnityAssetBundleVariantNameCollision
Test case for unity asset bundle variant name collisions

Open the AssetBundleBrowser in "Window/AssetBundle Browser"

go the the tab build

Build the bundles

it should give an error in the console

Building AssetBundle failed because hash collision was detected in the deterministic id generation.
Conflict happened between Asset "Assets/Bundles/VarBundles/x1/CommonMeta/TextFile.json" and "Assets/Bundles/VarBundles/x1/Common/TextFile.json".
UnityEditor.BuildPipeline:BuildAssetBundles(String, BuildAssetBundleOptions, BuildTarget)
AssetBundleBrowser.AssetBundleDataSource.AssetDatabaseABDataSource:BuildAssetBundles(ABBuildInfo) (at Library/PackageCache/com.unity.assetbundlebrowser@1.7.0/Editor/AssetBundleDataSource/AssetDatabaseABDataSource.cs:87)
AssetBundleBrowser.AssetBundleBuildTab:ExecuteBuild() (at Library/PackageCache/com.unity.assetbundlebrowser@1.7.0/Editor/AssetBundleBuildTab.cs:359)
UnityEditor.EditorApplication:Internal_CallDelayFunctions()


