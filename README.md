# MyWindowsSetup

This repository describes my prefered windows setup

- Windows 11 clean install

From the Windows Terminal:

# Install scoop
```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser # Needed to run a remote script the first time
irm get.scoop.sh | iex
scoop install python git
```

```powershell
winget install Microsoft.VisualStudioCode
```