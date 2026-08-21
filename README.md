# Progra III Div132 2026 c2

## Practicar con Git
- Instalar [Git Bash](https://git-scm.com/install/windows)
- Repasar para las próximas clases los [apuntes de Git](https://drive.google.com/drive/u/1/folders/1T1LEYs_H-NACabUJcdTXjodw8il6ZDsf)

### Guia rapida Git
1. Abrimos la consola de VSCode `Ctrl + j`
2. Elegimos la terminal en el menu `Git Bash`
3. Practicamos con los comandos esenciales de Git
    - (Para la primera vez) Creamos un repo en github y le damos a clone
    ```sh
    git clone https://github.com/profexabi/UTN2026_c2Div131.git
    ```

    - (Siempre antes de trabajar)
    ```sh
    # Comprobamos que no tenemos cambios sin guardar
    git status
    
    # Traemos los ultimos cambios
    git pull
    ```

    - Hacemos los cambios pertinentes en nuestro repo, y una vez que terminamos
    ```sh
    # Comprobamos el estado
    git status

    # Para guardar todo
    git add .

    # Registramos los cambios guardados con un mensaje
    git commit -m "Hecho cambio x, ble"

    # Ya con los cambios registrados, enviamos este codigo a nuestro repo
    git push origin main
    ```

---