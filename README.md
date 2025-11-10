# Tablero Digital — Monitoreo y Análisis Predictivo de Variables Industriales

### Universidad EAFIT — Ingeniería de Producción  
**Curso:** Digitalización de Plantas Productivas  
**Docente:** Miguel Ángel Carrillo  
**Autores:** [Nombres del equipo]  
**Año:** 2025

---

## Descripción del Proyecto

El presente proyecto consiste en el **diseño e implementación de un tablero digital interactivo** desarrollado en **Streamlit**, conectado a una base de datos **InfluxDB**.  
El tablero permite **visualizar, analizar y predecir** el comportamiento de las variables industriales provenientes de sensores instalados en una celda de producción simulada.

### Caso de uso: *Extreme Manufacturing*

La empresa **Extreme Manufacturing** busca digitalizar una celda de secado asistida por agitación mecánica.  
Para ello se instalan sensores que registran las condiciones del proceso:

- **DHT22:** mide temperatura y humedad relativa en la cámara de secado.  
- **MPU6050:** registra aceleraciones y vibraciones del motor de agitación.  

El sistema permite monitorear las variables en tiempo real e identificar posibles **fallas o desviaciones** mediante un modelo predictivo simple.

---

## Objetivos del Tablero

1. **Visualizar** las condiciones ambientales y mecánicas de la celda de producción.  
2. **Analizar** tendencias históricas mediante consultas dinámicas a InfluxDB.  
3. **Predecir** el comportamiento futuro de las variables (por ejemplo, temperatura o vibración).  
4. **Apoyar la toma de decisiones** de mantenimiento y control de calidad.

---

##  Dependencias y Librerías Utilizadas

A continuación, se listan las principales dependencias empleadas para el desarrollo del tablero digital:

| Librería | Descripción | Uso principal |
|-----------|--------------|----------------|
| **streamlit** | Framework para crear aplicaciones web interactivas en Python. | Interfaz del tablero y despliegue en Streamlit Cloud. |
| **pandas** | Herramienta para manipulación y análisis de datos. | Limpieza, filtrado y procesamiento de los registros. |
| **influxdb-client** | Cliente oficial de InfluxDB para Python. | Conexión y consultas al bucket “EXTREME_MANUFACTURING”. |
| **plotly** | Biblioteca de visualización interactiva. | Gráficos de líneas, tendencias y análisis visual. |
| **scikit-learn** | Librería de machine learning y modelado predictivo. | Implementación de regresión lineal y predicciones. |
| **numpy** | Librería para operaciones matemáticas y manejo de arreglos numéricos. | Cálculos y soporte a los modelos predictivos. |
| **datetime** | Módulo estándar de Python. | Manejo de rangos de tiempo y fechas en las consultas. |

---

