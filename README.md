

[🇪🇸 Español](#español) | [🇬🇧 English](#english)

---

## Español

# Data Entry & Data Cleaning — Portfolio

Transformo información desordenada en datos limpios y útiles. Este repositorio reúne scripts y ejemplos de **Data Cleaning**, **procesamiento CSV/JSON** y **automatización de tareas repetitivas** (sin scraping). Ideal para mostrar procesos claros, trazables y reproducibles.

### 🧰 Tecnologías

* Python · pandas · openpyxl · csv · json · logging · argparse

### 📦 Proyectos

* **01-data-cleaning/** · Limpieza y normalización de CSV → CSV/Excel limpio, reporte de calidad.
* **02-data-entry-assistant/** · Reordenar/estandarizar columnas para carga en sistemas.
* **03-csv-json-processing/** · Conversión, validación y merge entre CSV/JSON.
* **04-automation-scripts/** · Scripts para automatizar rutinas (validar, formatear, exportar).


### ▶️ Cómo ejecutar (ejemplo)

```bash
# 1) Crear entorno
python -m venv .venv
.venv\Scripts\activate   # Windows
# source .venv/bin/activate  # macOS/Linux

# 2) Instalar dependencias
pip install -r requirements.txt

# 3) Ejecutar un script de ejemplo
python 01-data-cleaning/src/main.py --input sample_data/orders_raw.csv --out-dir out
```

### ✅ Qué demuestra

* Limpieza reproducible con reglas claras (fechas, emails, montos, duplicados).
* Procesamiento CSV/JSON con validaciones y reportes.
* Automatización básica sin depender de scraping o integraciones externas.


### 📬 Contacto

* Rodrigo Altamiranda — Buenos Aires, AR
*[LinkedIn](https://www.linkedin.com/in/rodrigo-altamiranda/))*
* Email: *altamiranda.rod@gmail.com*

---

## English

# Data Entry & Data Cleaning — Portfolio

I turn messy information into clean, reliable datasets. This repository showcases **Data Cleaning**, **CSV/JSON processing**, and **automation for repetitive tasks** (no scraping). Built to highlight clear, traceable, and reproducible workflows.

### 🧰 Tech Stack

* Python · pandas · openpyxl · csv · json · logging · argparse

### 📦 Projects

* **01-data-cleaning/** · CSV cleanup/normalization → clean CSV/Excel + quality report.
* **02-data-entry-assistant/** · Reorder/standardize columns for system-friendly imports.
* **03-csv-json-processing/** · Convert, validate, and merge CSV/JSON.
* **04-automation-scripts/** · Scripts to automate routine formatting/validation/exports.


### ▶️ How to Run (example)

```bash
# 1) Create virtual env
python -m venv .venv
.venv\Scripts\activate   # Windows
# source .venv/bin/activate  # macOS/Linux

# 2) Install deps
pip install -r requirements.txt

# 3) Run a sample script
python 01-data-cleaning/src/main.py --input sample_data/orders_raw.csv --out-dir out
```

### ✅ What it demonstrates

* Reproducible cleaning with clear rules (dates, emails, amounts, duplicates).
* CSV/JSON processing with validations and reports.
* Basic automation without relying on scraping or external integrations.


### 📬 Contact

* Rodrigo Altamiranda — Buenos Aires, AR
*[LinkedIn](https://www.linkedin.com/in/rodrigo-altamiranda/))*
* Email: *altamiranda.rod@gmail.com*
