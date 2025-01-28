# Install.md

## Índice
- [Instalación](#instalacion)
- [Configuración](#configuracion)

---

## Instalación {#instalacion}

### Instalación de Git en Linux:
En distribuciones basadas en Debian/Ubuntu:
```bash
sudo apt update
sudo apt install git
```

---

## Configuración {#configuracion}

Una vez instalado Git, debemos configurarlo para usarlo correctamente.

### Configuración global:
1. Configura tu nombre de usuario:
```bash
git config --global user.name "Tu_Nombre"
```

2. Configura tu correo electrónico:
```bash
git config --global user.email "tuemail@example.com"
```

3. Verifica la configuración:
```bash
git config --list
```

### Configuración de tu editor predeterminado:
Puedes configurar tu editor preferido, por ejemplo, Visual Studio Code:
```bash
git config --global core.editor "code --wait"
```