# 🖼️ SI Image Processing Lab

Pipeline profesional de procesamiento de imágenes desarrollado con Python y Kedro, aplicando buenas prácticas modernas de ingeniería de software como CI/CD, pruebas automatizadas y análisis de calidad de código.

---

## 🚀 Tecnologías Utilizadas

- Python 3.11
- Kedro
- Poetry
- Pillow
- Pytest
- Ruff
- GitHub Actions
- SonarQube / SonarCloud

---

## 📌 Características

✅ Procesamiento automatizado de imágenes  
✅ Rotación dinámica de imágenes  
✅ Aplicación de filtros con Pillow  
✅ Marca de agua personalizada  
✅ Pipeline reproducible con Kedro  
✅ Validación de calidad de código  
✅ Integración continua con GitHub Actions  
✅ Pruebas automatizadas con Pytest  

---

## 📂 Estructura del Proyecto

```bash
si-image-processing-lab/
│
├── conf/
│   ├── base/
│
├── data/
│   ├── 01_raw/
│   └── 03_primary/
│
├── src/
│   └── si_image_processing/
│
├── tests/
│
├── .github/workflows/
│
├── pyproject.toml
├── sonar-project.properties
└── README.md
```

---

## ⚙️ Instalación

Clonar el repositorio:

```bash
git clone https://github.com/arrietaramirezjarol9-ui/si-image-processing-lab.git
```

Ingresar al proyecto:

```bash
cd si-image-processing-lab
```

Instalar dependencias:

```bash
poetry install
```

---

## ▶️ Ejecutar el Pipeline

```bash
poetry run kedro run
```

---

## 🧪 Ejecutar Pruebas

```bash
poetry run pytest
```

---

## 🔍 Análisis de Calidad

```bash
poetry run ruff check .
```

---

## 📸 Resultado del Proyecto

El pipeline procesa imágenes aplicando:

- Rotación
- Filtros
- Marca de agua
- Exportación automatizada

---

## 🔄 CI/CD

El proyecto utiliza GitHub Actions para:

- Ejecutar pruebas automáticas
- Validar calidad del código
- Verificar Pull Requests

---

## 📚 Aprendizajes

Este proyecto permitió reforzar conocimientos en:

- Ingeniería de software
- Automatización de pipelines
- Procesamiento de imágenes
- Control de versiones con Git
- Integración continua
- Calidad de código

---

## 👩‍💻 Autora

Jermain Arrieta Ramirez  
Estudiante de Ingeniería de Sistemas

---

## 📸 Resultado

| Imagen Original | Imagen Procesada |
|---|---|
| ![Original](data/01_raw/marte.jpg) | ![Procesada](data/03_primary/marte_processed.jpg) |

## ⭐ Repositorio

Si te gustó el proyecto, puedes darle una estrella ⭐ al repositorio.
