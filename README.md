# Inicializar o Git Flow
```bash
git flow init
```

# Criar uma nova feature
```bash
git flow feature start <NOME_DA_FEATURE>
```

# Adicionar e commitar as mudanças
```bash
git add .
git commit -m "Implementa <descrição da feature>"
```
# Finalizar a feature (isso faz merge para develop e deleta a branch)
```bash
git flow feature finish <NOME_DA_FEATURE>
```

# Criar uma release
```bash
git flow release start 1.0.1
```

# Revisar, testar e commitar mudanças finais (se necessário)
```bash
git add .
git commit -m "Ajustes finais para a release 1.0.1"
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
