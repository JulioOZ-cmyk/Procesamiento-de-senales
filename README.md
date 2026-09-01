# Digital Image Signal

Repositorio para el desarrollo Laboratorios y proyectos de **Procesamiento Digital de Imágenes y Señales** utilizando Python.

---

## 1. Requisitos

Instalar:

* [Anaconda](https://www.anaconda.com/download)
* [Git](https://git-scm.com/downloads)
* Cuenta de GitHub

Verificar:

```powershell
conda --version
git --version
```


## 2. Crear el entorno Python

Crear un entorno independiente con Python 3.10:

```powershell
conda create -n digital_image_signal python=3.10 -y
```

Activar:

```powershell
conda activate digital_image_signal
```

Verificar:

```powershell
python --version
```

Debe mostrar:

```text
Python 3.10.x
```

---

## 3. Instalar las dependencias

```powershell
pip install -r requirements.txt
```

Si se agregan nuevas librerías, actualizar:

```powershell
pip freeze > requirements.txt
```

---

## 4. Estructura del proyecto

```text
Digital_Image_signal/
¦
+-- README.md
+-- requirements.txt
+-- .gitignore
¦
+-- src/              # Código fuente
¦
+-- notebooks/        # Jupyter Notebooks
¦
+-- data/             # Datasets
¦   +-- raw/          # Datos originales
¦   +-- processed/    # Datos procesados
¦
+-- examples/         # Ejemplos y pruebas
¦
+-- results/          # Resultados, figuras y experimentos
```



## 5. Ejecutar el proyecto

Activar el entorno:

```powershell
conda activate digital_image_signal
```

Abrir el proyecto en VS Code.

Abrir:
   notebooks/secuencias_operations.ipynb

Seleccionar como kernel:
   digital_image_signal

Ejecutar las celdas.


## LIBRERIAS A INSTALAR
### Librerías utilizadas

NumPy: Permite trabajar con arreglos y secuencias numéricas, realizar operaciones matemáticas y manipular señales discretas de forma eficiente.

Matplotlib : Permite visualizar gráficamente las señales, tanto en tiempo continuo (`plot`) como en tiempo discreto (`stem`).

IPykernel: Permite ejecutar los notebooks de Jupyter utilizando el entorno de Python seleccionado.

Jupyter: Proporciona el entorno para crear y ejecutar notebooks (`.ipynb`), combinando código, ecuaciones, explicaciones y gráficos.
