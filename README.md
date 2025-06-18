# vex-ru.github.io/codeiq


# Утилиты для портирования 

## JS Beautifier

Команда для PowerShell для деобфускации js

```powershell
$env:NODE_OPTIONS="--max-old-space-size=4096"; npx prettier --write dist/main.bundle.js; Remove-Item Env:NODE_OPTIONS
```

