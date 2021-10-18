# Windows terminal
* choose windows terminal as default terminal
* choose powershell as default shell (.net core)

```
winget install JanDeDobbeleer.OhMyPosh
``` 

* runnable oh-my-posh.exe
  
* install Caskaydia Cove Nerd Font
  * https://www.nerdfonts.com/font-downloads

* Clone ohmyposh config
```powershell
cd ~/repos
git clone https://github.com/jakubjenis/prompt.git
```

* Find out where powershell profile should be

```powershell
echo $PROFILE 
```

* Create the file
  * TODO - how to create file with path on windows?
* Edit profile

```powershell
notepad $PROFILE 
```

* Paste profile content
```
oh-my-posh --init --shell pwsh --config C:\Users\jakub\repos\prompt\ohmyposh.json | Invoke-Expression
```

#Themes
C:\Users\jakub\AppData\Local\Programs\oh-my-posh\themes

## Github CLI
```
winget install GitHub.cli --source winget
gh auth login
```

## Terminal enhancements
```
Install-Module -Name Terminal-Icons -Repository PSGallery
Install-Module PSReadLine -RequiredVersion 2.2.0-beta1 -AllowPrerelease
Install-Module -Name z
```

## WSL
