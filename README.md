## HoloLens-AzurePipelineMRTKv1

[![Build Status](https://dev.azure.com/guitarrapc-oss/HoloLens%20App/_apis/build/status/guitarrapc.HoloLens-AzurePipelineMRTKv1?branchName=master)](https://dev.azure.com/guitarrapc-oss/HoloLens%20App/_build/latest?definitionId=5&branchName=master)

Unity Build (IL2CPP)

```
Start-UnityEditor -Project . -Version 2018.3.13f1 -ExecuteMethod HoloToolkit.Unity.BuildDeployTools.BuildSLN -BuildTarget WSAPlayer -Wait -BatchMode
```

MSBuild (IL2CPP C++ build)

```
"C:\Program Files (x86)\Microsoft Visual Studio\2019\Professional\MSBuild\Current\Bin\MSBuild.exe" UWP/UnitySamplev1.sln /p:PlatformToolset=v142;Configuration=Release;Platform=x86;AppxBundle=Always;AppxBundlePlatforms=x86
```

appx output at

> UWP\AppPackages\UnitySamplev1\UnitySamplev1_1.0.0.0_Test
