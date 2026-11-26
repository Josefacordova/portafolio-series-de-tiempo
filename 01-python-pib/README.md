# Proyecto 1 (Python): PIB nominal de Chile

- **Qué mide:** valor de los bienes y servicios finales producidos en Chile, a precios corrientes (incluye inflación).
- **Unidad:** miles de millones de pesos.
- **Fuente:** Banco Central de Chile, serie `F032.PIB.FLU.N.CLP.EP18.Z.Z.0.T`.
- **Período y frecuencia:** 1996 T1 a 2026 T2, trimestral (122 datos).

## Hallazgos
- Tendencia creciente: el último dato es cerca de 11 veces el primero (en parte por inflación).
- Estacionalidad: el cuarto trimestre suele estar sobre la tendencia y el tercero bajo ella.
- Anomalía: en el segundo trimestre de 2020 (pandemia) cae un 5,0% respecto del mismo trimestre de 2019.

## Archivos
- `reporte_1_pib.ipynb`: notebook de Python.
- `PIB(in).csv`: datos.

## Cómo abrirlo
Abrir el notebook en Jupyter o Google Colab, con el CSV en la misma carpeta (en Colab hay que subirlo), y ejecutar todas las celdas. Requiere `pandas` y `matplotlib`.
