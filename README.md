# Proyecto RAWG - Análisis de Videojuegos

## Descripción
Este proyecto utiliza la API de RAWG para extraer, procesar y analizar datos de videojuegos. Aplicamos conceptos de los Módulos 1 y 2 del Bootcamp de Data Science de Hack a Boss: programación en Python, manejo de APIs, limpieza de datos, análisis exploratorio y visualización.

## Estructura de Carpetas
```
Proyecto_RAWG/
│
├── data/
│   ├── raw/             # Datos originales extraídos desde la API
│   └── processed/       # Datos limpios y preparados para análisis
│
├── notebooks/
│   ├── 1_extraccion_datos_rawg.ipynb
│   ├── 2_limpieza_y_procesamiento.ipynb
│   ├── 3_analisis_exploratorio.ipynb
│   └── 4_visualizaciones_y_conclusiones.ipynb
│
├── scripts/             # Funciones auxiliares o módulos reutilizables
├── outputs/
│   └── plots/           # Gráficos y visualizaciones generadas
├── docs/                # Documentación adicional
└── README.md            # Este archivo
```

## Requisitos
- Python 3.8+
- Paquetes: `requests`, `pandas`, `tqdm`, `matplotlib`, `seaborn`

Instalación de dependencias:
```bash
pip install requests pandas tqdm matplotlib seaborn
```

## Configuración
1. Regístrate en [RAWG API](https://rawg.io/apidocs) y obtén tu `API_KEY`.
2. En el notebook `1_extraccion_datos_rawg.ipynb`, reemplaza `"TU_API_KEY"` con tu clave.

## Ejecución
1. Abre los notebooks en Jupyter o Google Colab siguiendo el orden:
   - `1_extraccion_datos_rawg.ipynb`
   - `2_limpieza_y_procesamiento.ipynb`
   - `3_analisis_exploratorio.ipynb`
   - `4_visualizaciones_y_conclusiones.ipynb`
2. Ejecuta cada celda paso a paso y guarda los outputs en `data/processed` y `outputs/plots`.

## Contribución en Equipo
- Cada miembro puede trabajar en su notebook asignado.
- Usar control de versiones (Git) para combinación de cambios.
- Revisar pull requests con comentarios antes de mergear.
- Documentar cualquier función en la carpeta `scripts/`.

---