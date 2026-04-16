# Pasos a Seguir

```markdown
1. Instalar fuente (fonts/)
2. Copiar settings.json
3. Instalar extensiones
```

### Comando para generar la lista de extesiones de vscode
```markdown
- code --list-extensions > extensions.txt
```

### Comando para instalar todas las extensiones
```markdown
- for /f %i in (extensions.txt) do code --install-extension %i
```