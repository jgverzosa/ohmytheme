# OhMyTheme
Custom PowerShell UI. 

### Requirements
- git-pos
- oh-my-posh
```
> code `$PROFILE`
Import-Module posh-git
oh-my-posh init pwsh --config ~/.mytheme.omp.json | Invoke-Expression
Import-Module -Name Terminal-Icons
$env:VIRTUAL_ENV_DISABLE_PROMPT = 1
```

## License

MIT
