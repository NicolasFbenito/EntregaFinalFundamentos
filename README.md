# TPE Ciencia de Datos 2026 – Global Food & Nutrition

Trabajo Práctico Especial para la materia **Fundamentos de la Ciencia de Datos** (Cursada 2026).

* **Grupo:** 26v
* **Ayudante asignado:** Duilio Deangeli
* **Integrantes:**
  * Benito, Nicolás
  * Raffaeli, Esteban
  * Holzmann, Aitor

---

## Estructura del Proyecto

* `main.ipynb`: Notebook interactivo con la totalidad del análisis exploratorio, limpieza de datos y validación de hipótesis.
* `INFORME_FINAL.pdf`: Informe ejecutivo detallando la metodología, hallazgos y conclusiones.
* `INFORME_FINAL.md`: Versión Markdown del informe final.
* `data/global_food_nutrition.csv`: Conjunto de datos base utilizado para el trabajo.
* `requirements.txt`: Dependencias del entorno de Python.

---

## Instrucciones de Instalación y Ejecución

### 1. Clonar el repositorio
```bash
git clone https://github.com/NicolasFbenito/EntregaFinalFundamentos
cd EntregaFinalFundamentos
```

### 2. Crear y activar el entorno virtual

* **En Linux / macOS:**
  ```bash
  python3 -m venv env
  source env/bin/activate
  ```
* **En Windows:**
  ```bash
  python -m venv env
  env\Scripts\activate
  ```

### 3. Instalar dependencias
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Ejecución del Notebook
Con el entorno virtual activado, iniciar Jupyter:
```bash
jupyter notebook main.ipynb
```
*(O bien abrir la carpeta en VS Code / PyCharm y seleccionar el kernel correspondiente al entorno `env`).*


### Error en windows:
Si la carpeta del repo es muy profunda, ejecutar en powershell:    New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" -Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force