# Wsl for windows 10
#

# wsl 2 for windows 11

# 1

```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```

# 2
```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

# 3

```
Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform -NoRestart
```

# 4

```
wsl --set-default-version 2
```
