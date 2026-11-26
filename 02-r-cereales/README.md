# Proyecto 2 (R): Índice de precios de cereales

- **Qué mide:** evolución del precio internacional de los cereales (índice, 2014-2016 = 100).
- **Fuente:** FAO, vía Base de Datos Estadísticos del Banco Central de Chile, serie `F019.PPBA.INP.46B.M`.
- **Período y frecuencia:** enero 2010 a agosto 2026, mensual (200 datos).

## Hallazgos
- No hay una tendencia única: dominan ciclos de varios años (alzas en 2011-2013 y 2021-2022).
- Estacionalidad débil: no hay un patrón mensual marcado.
- Mínimo: 86,0 (noviembre 2016). Máximo: 173,5 (mayo 2022).
- Último dato: 116,3 (agosto 2026), cercano al promedio del período (115,2).

## Archivos
- `reporte_2_cereales.ipynb`: notebook con el código y los gráficos.
- `reporte_2_cereales.R`: el mismo código como script de R.
- `EI_PROD_BAS_AL (Cereales).xlsx`: datos.

## Cómo abrirlo
- **Google Colab:** abrir el notebook, elegir entorno de ejecución R, subir el Excel y ejecutar todo.
- **RStudio:** abrir el `.R`, fijar como directorio de trabajo la carpeta del archivo y ejecutar. Requiere `readxl`, `dplyr`, `ggplot2`, `scales` y `tidyr`.
