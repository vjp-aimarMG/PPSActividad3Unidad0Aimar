# GitHub.md

## Abrir una cuenta en GitHub

1. Ve a [https://github.com/](https://github.com/).
2. Haz clic en **Sign up**.
3. Completa el formulario con tu correo, contraseña y nombre de usuario.
4. Sigue los pasos para verificar tu correo y finalizar la creación de la cuenta.

---

## Iniciar sesión en GitHub

1. Ve a [https://github.com/login](https://github.com/login).
2. Ingresa tu correo y contraseña.
3. Haz clic en **Sign in**.

---

## Funcionamiento básico de GitHub

### Crear un repositorio:
1. Una vez logueado, haz clic en el botón **New** en la página principal.
2. Rellena el nombre del repositorio y, opcionalmente, una descripción.
3. Elige si deseas que sea público o privado.
4. Haz clic en **Create repository**.

### Subir un proyecto a GitHub:
Después de crear un repositorio:
1. Inicializa tu repositorio local y enlázalo al remoto:
```bash
git remote add origin <url_del_repositorio>
```

2. Sube los cambios:
```bash
git push -u origin <rama>
```

### Clonar un repositorio desde GitHub:
1. Copia la URL del repositorio desde el botón verde **Code**.
2. Usa el siguiente comando:
```bash
git clone <url_del_repositorio>
```

### Crear un Pull Request:
1. Haz un fork del repositorio.
2. Realiza cambios en tu copia del repositorio.
3. Sube los cambios a una nueva rama y ve a la página del repositorio original.
4. Haz clic en **Pull Requests** > **New Pull Request**.
