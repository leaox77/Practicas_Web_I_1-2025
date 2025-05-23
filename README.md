# Practicas_Web_I_1-2025

## Instrucciones para clonar el repositorio

1. Abre una terminal o consola de comandos.
2. Navega a la carpeta donde deseas clonar el repositorio.
3. Ejecuta el siguiente comando:

    ```bash
    git clone https://github.com/leaox77/Practicas_Web_I_1-2025.git
    ```

4. Ingresa al directorio del repositorio clonado:

    ```bash
    cd Practicas_Web_I_1-2025
    ```

## Instruccione spara crearse una nueva rama

1. Asegúrate de estar en el directorio del repositorio.
2. Actualiza la información del repositorio remoto:

    ```bash
    git pull origin main
    ```

3. Crea una nueva rama y cámbiate a ella (reemplaza `nombre-de-tu-rama` por el siguiente formato 'ApellidoP_ApellidoM_Nombres'):

    ```bash
    git checkout -b nombre-de-tu-rama
    ```

4. Verifica que estás en la nueva rama:

    ```bash
    git branch
    ```

5. Actualiza desde main antes de hacer tus cambios

    ```bash
    git pull origin main
    ```

## Instrucciones para subir tus cambios (solo a tu rama)

1. Asegúrate de haber guardado y agregado tus archivos modificados:

    ```bash
    git add .
    ```

2. Realiza un commit con un mensaje descriptivo:

    ```bash
    git commit -m "Descripción de los cambios realizados"
    ```

3. Sube tus cambios a tu rama en el repositorio remoto:

    ```bash
    git push origin nombre-de-tu-rama
    ```

4. Verifica en GitHub que tus cambios se hayan subido correctamente.