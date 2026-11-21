# U3 – Análisis Supervisado: predicción del resultado de partidos de la NFL

Modelo de clasificación que predice si el equipo local gana un partido de la NFL, usando solo información disponible antes del partido (forma reciente de los equipos).

## Datos
- Fuente: [nflverse / nfldata](https://github.com/nflverse/nfldata), licencia CC BY 4.0.
- `data/raw/`: dataset original sin modificar.
- `data/clean/`: dataset limpio y dataset con variables para el modelo.

## Cómo ejecutar
1. `python3 -m venv .venv && source .venv/bin/activate`
2. `pip install -r requirements.txt`
3. `jupyter notebook` y abrir `notebooks/analisis_supervisado.ipynb`

## Modelos
Línea base, regresión logística, árbol de decisión y Random Forest, optimizados con validación cruzada temporal. Partición: 1999–2021 entrenamiento, 2022 en adelante prueba.

## Nota
El código en R de la raíz del repositorio pertenece al proyecto nflverse-data y no forma parte de este análisis.