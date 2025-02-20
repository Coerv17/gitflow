# Inicializar o Git Flow
```bash
git flow init
```

# Criar uma nova feature
```bash
git flow feature start <NOME_DA_FEATURE>
```

# Finalizar a feature
```bash
git flow feature finish <NOME_DA_FEATURE>
```

# Criar uma release
```bash
git flow release start 1.0.1
```

# Finalizar a release (isso já cria a tag automaticamente!)
```bash
git flow release finish 1.0.1
```

# Fazer push de todas as branches (develop, master e outras)
```bash
git push --all
```

# Fazer push das tags criadas automaticamente
```bash
git push --tags
```
