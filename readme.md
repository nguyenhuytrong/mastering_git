## Welcome to Git!

- Tutorial: https://www.youtube.com/watch?v=S7XpTAnSDL4
### Typical workflow
1. Create a local main in your comp and a repo on GitHub
2. Clone the repo
2. Create a new **branch** from the **main** or another branch
3. Make your changes
4. **Push** the branch to the remote repo
5. Open the **Pull Request** and **Merge** changes
6. **Pull** the merged changes into your **local main** 
7. Repeat from step 2

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

### Branch
I'm currently working with the `feature-branch`.
It's absolutely fun and helpful. I'm going to learn
how to cooperate with others using Git & GitHub.

### I love Git & GitHub
