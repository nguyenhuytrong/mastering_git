# Hello, Git!
### Install Posh-Git
To keep track of what is the 'head' is currently on. I mean when use the 'checkout'.
and it's shown in the terminal

Steps:
```powershell
Install-Module posh-git -Scope CurrentUser
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
Import-Module posh-git
Add-PoshGitToProfile
. $PROFILE
```

