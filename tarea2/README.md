# Tarea 2 - EDA, Personas desaparecidas en México
La tarea 2 de la materia de **Almacenes y Minería de Datos** tiene como objetivo realizar un análisis exploratorio de datos de un dataset de personas desaparecidas en México que en este caso es el dataset del archivo <u>***`tot_reg_desap.csv`***</u>, mediante la aplicación de la metodología ***CRISP-DM***, creando un informe con los resultados obtenidos, además de un archivo `csv` con el dataset después del proceso de limpieza.  

## Equipo 2:
* **Escobar Gonzalez Isaac Giovani** - 321336400
* **Garduño Escobar Kevin Jonathan** - 321070629
* **Pinacho Báez Arlet** - 320287828
* **Sautto Ramirez Seldon** - 321084163

## Requerimientos:
Para la visualización de esta tarea se requiere tener instalado lo siguiente:
* Python 3.8 o superior (Si no lo tienes instalado, puedes descargarlo desde [aquí](https://www.python.org/downloads/))
* Quarto 1.9 o superior (Si no lo tienes instalado, puedes descargarlo desde [aquí](https://quarto.org/docs/download/))

## Instrucciones para ejecutar el código:
Seguir estos pasos para clonar el repositorio, crear el entorno virtual, instalar las dependencias y ejecutar el código:
1. Clonar el repositorio de GitHub
```bash
git clone https://github.com/Seldon1128/AlmacenesYMineriaDatos.git
```
2. Navegar al directorio del proyecto
```bash
cd AlmacenesYMineriaDatos/tarea2
```
3. Crear un entorno virtual
```bash
python -m venv env
```
4. Activar el entorno virtual
- En Windows:
```bash
.\env\Scripts\activate
```
- En macOS/Linux:
```bash
source env/bin/activate
```
5. Instalar las dependencias
```bash
pip install -r requirements.txt
```
6. Crear la carpeta `data`
```bash
mkdir data
```
7. Colocar el archivo `tot_reg_desap.csv` dentro de la carpeta `data`
8. Navegar a la carpeta `desap_mex`
```bash
cd desap_mex
```
9. Ejecutar el código para la visualización
```bash
quarto render
```
También puedes ejecutar el código para la visualización utilizando el siguiente comando:
```bash
quarto preview
```
Esto abrirá una ventana en tu navegador con la visualización del análisis exploratorio de datos de personas desaparecidas en México.