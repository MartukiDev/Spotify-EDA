# Anatomía de una canción popular — Análisis EDA sobre Spotify Tracks Dataset

Proyecto final de **Ciencia de Datos con Python (Optativo II)** — Universidad de Playa Ancha · Ingeniería en Informática · 2026.

## Integrantes

- Martín Maturana
- Vicente Tapia
- Juan Pablo Poblete
- Moisés Espinoza
- Benjamín Burgos

**Institución:** Universidad de Playa Ancha (UPLA) · Primer Semestre 2026  
**Docente:** Prof. Diego Saavedra Lizana

---

## Pregunta de investigación

> ¿Qué características de audio (danceability, energy, valence, tempo) predicen mejor la popularidad de una canción en Spotify, y varía este patrón según el género musical?

---

## Navegación del proyecto

| Documento | Contenido |
|---|---|
| [📓 Notebook en nbviewer](https://nbviewer.org/github/MartukiDev/Spotify-EDA/blob/main/notebooks/spotify_eda_proyecto.ipynb) | Código fuente + gráficos ejecutados |
| [📄 Análisis completo](docs/analisis.md) | Interpretaciones, hallazgos y conclusiones |

*(Reemplazar `MartukiDev` con el nombre de usuario de GitHub antes de publicar)*

---

## Dataset

| Campo | Detalle |
|---|---|
| **Nombre** | Spotify Tracks Dataset |
| **Fuente** | [Kaggle — maharshipandya](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) |
| **Archivo** | `data/dataset.csv` |
| **Formato** | CSV |
| **Filas** | ~114,000 canciones |
| **Columnas** | 20 (popularidad, características de audio, género, etc.) |

> **Nota:** El archivo `dataset.csv` no está incluido en este repositorio por su tamaño. Ver instrucciones de instalación.

---

## Instalación local

```bash
git clone https://github.com/MartukiDev/Spotify-EDA.git
cd Spotify-EDA
pip install -r requirements.txt
# Descargar dataset.csv desde https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset
# y colocarlo en la carpeta data/
```

Luego abrir `notebooks/spotify_eda_proyecto.ipynb` en VS Code con la extensión Jupyter y ejecutar **Run All**.

---

## Estructura del repositorio

```
Spotify-EDA/
├── data/
│   └── .gitkeep                     # El dataset NO se sube a git
├── notebooks/
│   └── spotify_eda_proyecto.ipynb   # Código + 7 gráficos
├── docs/
│   └── analisis.md                  # Interpretaciones y conclusiones
├── figures/                         # PNGs generados al ejecutar el notebook
│   └── .gitkeep
├── .gitignore
├── README.md
└── requirements.txt
```

---

## Reproducibilidad

- Semilla fija: `random_state=42` en todas las operaciones aleatorias
- Versiones exactas de librerías en `requirements.txt`
- El notebook se ejecuta de arriba a abajo con **Run All** sin errores

---

*Proyecto desarrollado por: Martín Maturana, Vicente Tapia, Juan Pablo Poblete, Moisés Espinoza, Benjamín Burgos — UPLA 2026*
