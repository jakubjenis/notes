# Windows terminal
* choose windows terminal as default terminal
* choose powershell as default shell (.net core)

```
winget install JanDeDobbeleer.OhMyPosh
``` 

* runnable oh-my-posh.exe
  
* install Caskaydia Cove Nerd Font
  * https://www.nerdfonts.com/font-downloads

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
oh-my-posh --init --shell pwsh --config C:\Users\jakub\repos\prompt\ohmyposh-shanselman.json | Invoke-Expression
```

## Github CLI
```
winget install GitHub.cli --source winget
gh auth login
```

## WSL
