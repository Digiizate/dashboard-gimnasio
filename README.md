# Dashboard · Asistencia en la cadena de gimnasios

Tablero interactivo (HTML + JavaScript + Plotly) con filtros en vivo, 6 pestañas, carrera animada de
disciplinas, calendario de actividad, mapa de calor, diagrama Sankey y tabla descargable.

No necesita servidor: es una página estática que se publica con GitHub Pages.

| Archivo | Qué es |
|---|---|
| `index.html` | El dashboard (diseño, filtros y gráficos) |
| `data.js` | Los datos de asistencia (33.208 registros sintéticos) |
| `plotly.min.js` | Librería de gráficos (se incluye para que funcione sin depender de internet) |

Para verlo en tu PC basta con abrir `index.html` con doble clic.

Los datos son sintéticos y salen de los scripts SQL del proyecto (`gimnasio_db`).
