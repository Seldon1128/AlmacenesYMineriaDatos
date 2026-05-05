# Tarea 3 - Reglas de asociación y clasificación
La tarea 3 de la materia de **Almacenes y Minería de Datos** tiene como objetivo aplicar distintos algoritmos de minería de datos tanto para la generación de reglas de asociación como para el desarrollo de un modelo de clasificación para predecir *ESTATUS_VICTIMA*, a partir de un dataset de personas desaparecidas en México que en este caso es el dataset del archivo <u>***`data_secretariado.csv`***</u>.

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
cd AlmacenesYMineriaDatos/tarea3
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
7. Colocar el archivo `data_secretariado.csv` dentro de la carpeta `data`
8. Navegar a la carpeta `reglas_asoc_secretariado`
```bash
cd reglas_asoc_secretariado
```
9. Ejecutar el código para la visualización
```bash
quarto render
```
También puedes ejecutar el código para la visualización utilizando el siguiente comando:
```bash
quarto preview
```
Esto abrirá una ventana en tu navegador con la visualización de la implementación, aplicación y análisis de los distintos algoritmos.