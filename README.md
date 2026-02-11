# Data Science - Python Learning Project

Proyecto para aprender Data Science con Python y Google Colab.

## Estructura del Proyecto

```
data-science/
├── src/                    # Código fuente principal
│   ├── models/             # Modelos de datos y ML
│   ├── services/           # Lógica de negocio
│   └── utils/              # Utilidades y helpers
├── notebooks/              # Jupyter/Colab notebooks
├── data/                   # Datasets
│   ├── raw/                # Datos sin procesar
│   └── processed/          # Datos procesados
├── tests/                  # Tests unitarios
├── requirements.txt        # Dependencias del proyecto
└── .env.example            # Variables de entorno ejemplo
```

## Requisitos

- Python 3.10+
- pip

## Instalación

```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
source venv/bin/activate  # macOS/Linux

# Instalar dependencias
pip install -r requirements.txt
```

## Uso con Google Colab

1. Sube los notebooks de la carpeta `notebooks/` a Google Colab
2. O conecta tu Google Drive y clona este repositorio:

```python
from google.colab import drive
drive.mount('/content/drive')

%cd /content/drive/MyDrive
!git clone <tu-repo-url>
```

## Librerías Principales

- **pandas**: Manipulación de datos
- **numpy**: Operaciones numéricas
- **matplotlib/seaborn**: Visualización
- **scikit-learn**: Machine Learning
- **jupyter**: Notebooks locales

## Autor

Omar Martinez

## Licencia

MIT
