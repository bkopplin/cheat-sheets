# Powershell
## Environment variables
Set
```PowerShell
$Env:Foo=bar
```
Get
```PowerShell
$Env:Path
```
Remove
```PowerShell
Remove-Item Env:\SOME_VARIABLE
```
See all set env variables
```PowerShell
Get-ChildItem Env:
```

## Other
source of an executable
```
(Get-Command python).Source
```
Emacs Edit Mode: 
```
Set-PSReadLineOption -EditMode Emacs
```
