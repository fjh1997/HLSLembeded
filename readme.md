

# DirectXShader embedded in executable example
![nBodyGravity GUI](D3D12nBodyGravity.png)

## build 
```
cmd.exe /k "C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Auxiliary\Build\vcvars64.bat"
nuget install packages.config  -OutputDirectory packages
msbuild /p:Configuration=Release
```