# Los Parsimoniosos

Este proyecto está pensado para ejecutarse en Visual Studio Code con Conda y para correr únicamente el notebook principal:

- Script_trabajo_final.ipynb

## Requisitos

- VS Code
- Conda o Miniconda
- Python 3.12.x
- Internet para descargar los datos desde las URLs del notebook

## 1. Crear el entorno con conda

Abre una terminal en la carpeta del proyecto y ejecuta:

```bash
conda env create -f environment.yml
```

Luego activa el entorno:

```bash
conda activate los_parsimoniosos
```

## 2. Registrar el entorno en Jupyter

Para que el entorno aparezca dentro de VS Code como kernel de Python, ejecuta:

```bash
python -m ipykernel install --user --name los_parsimoniosos --display-name "Python (los_parsimoniosos)"
```

## 3. Abrir y ejecutar el notebook en VS Code

1. Abre Visual Studio Code.
2. Abre el archivo [Script_trabajo_final.ipynb](Script_trabajo_final.ipynb).
3. En la esquina superior derecha del notebook, selecciona el kernel:
   - Python (los_parsimoniosos)
4. Ejecuta las celdas en orden.

## 4. Datos usados por el notebook

El notebook descarga los datos directamente desde las URLs internas del INEEd, por lo que no necesitas tener archivos locales adicionales para correrlo.
