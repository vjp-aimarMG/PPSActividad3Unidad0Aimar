# UsoGit.md

## Comandos principales de Git

### Inicializar un repositorio:
```bash
git init
```

### Clonar un repositorio existente:
```bash
git clone <url_del_repositorio>
```

### Ver el estado del repositorio:
```bash
git status
```

### Añadir cambios al área de preparación (staging):
```bash
git add <archivo>
```
O para añadir todos los archivos:
```bash
git add .
```

### Confirmar los cambios:
```bash
git commit -m "Mensaje del commit"
```

### Ver el historial de commits:
```bash
git log
```

### Subir cambios al repositorio remoto:
```bash
git push origin <rama>
```

### Descargar cambios del repositorio remoto:
```bash
git pull
```

### Crear una nueva rama:
```bash
git branch <nombre_de_la_rama>
```

### Cambiar de rama:
```bash
git checkout <nombre_de_la_rama>
```
