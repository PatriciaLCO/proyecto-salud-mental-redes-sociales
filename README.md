#  Redes Sociales y Salud Mental
**Análisis predictivo del impacto en estrés y productividad** (30k registros)

##  Contexto de negocio
¿**Cómo afecta el uso de redes sociales al estrés laboral y productividad**?

##  Dataset
- **30.000 filas** | **21 columnas**
- Tiempo redes, notificaciones, estrés, productividad, burnout, sueño...

##  Proceso
### Limpieza
- Nulos interpolados, outliers tratados
### EDA
- Correlaciones, segmentación por red social/género
### Machine Learning
- **K-Means**: segmentación usuarios
- **Random Forest**: estrés (81% accuracy), productividad (80.9%)

##  Insights clave
- Instagram/Twitter → mayor estrés
- Focus apps + pausas → +15% productividad

##  Stack
Python | pandas | scikit-learn | SQL | Power BI

##  Archivos
- [Notebook completo](PROYECTO-SALUD-MENTAL.ipynb)
- [Dashboard Power BI](Presentacion-Proyecto-Final-Neoland.pdf)
