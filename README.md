## 👨‍🏫 Autor

```bash
Proyecto desarrollado aplicando conceptos de Big Data, Vs Code, Python, MongoDB y Jenkins.
Jaime Llanos Bardales
Fecha: 17.10.2025
```




🧱 Estructura de Datos Simulada
Archivo: visitantes.csv
| id_visitante | pais_origen | edad | genero | destino | region | fecha_visita | dias_estadia | gasto_total | medio_transporte |
|---------------|-------------|-------|---------|----------|----------|----------------|---------------|------------------|
| V0001 | Perú | 28 | M | Machu Picchu | Cusco | 2025-03-14 | 3 | 1200 | Avión |
| V0002 | Chile | 35 | F | Lago Titicaca | Puno | 2025-04-02 | 5 | 2100 | Bus |

🔍 Fases del Proyecto
🧩 Fase 1 – Creación de Archivos
Crear carpetas data, database, reports, ci, git y scripts y estructura base del proyecto usando os y pathlib en tiempo de ejecución
🧩 Fase 2 – Definición de Esquema
Generar un archivo base CSV (base.csv) con la estructura indicada.
🧩 Fase 3 – Generación de Datos Aleatorios
Generar un archivo CSV (visitantes.csv) con 3000 registros simulados, que incluya campos nulos, NA, entre otros
🧩 Fase 4 – ETL (Limpieza de Datos)
•	Eliminar duplicados
•	Rellenar valores nulos en campos de transporte o destino
•	Formatear fechas
•	Validar tipos de datos
Guardar como visitantes_clean.csv.
🧩 Fase 5 – Carga en MongoDB
Crear base de datos TurismoPeru_2025 y colección Visitantes
Insertar los registros limpios desde CSV.
🧩 Fase 6 – Visualización de Datos
Usar matplotlib y pandas para mostrar:
1.	Gráfico de barras: número de visitantes por región
2.	Gráfico circular: distribución por país de origen
3.	Gráfico de línea: tendencia mensual de visitas
4.	Histograma: gasto promedio por visitante
