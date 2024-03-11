# Powershell
## Environment variables[^1]
Set an environment variable for current session
```PowerShell
$Env:Foo=bar
```
Set environment variable globally for all future sessions
```PowerShell
setx SOME_VARIABLE some-value
```
Get
```PowerShell
$Env:Path
```
Unset Environment variable in current session
```PowerShell
Remove-Item Env:\SOME_VARIABLE
```
See all currently set environment variables
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

[^1]: [Node.js Docs](https://docs.cypress.io/guides/references/proxy-configuration#View-unset-and-set-environment-variables)
