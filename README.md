# 📦 Análisis de Optimización Logística: Despachos Textiles

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/bad## 👨‍💻 Sobre el Autor

**Andrés Ohannessian** - Analista de Datos | Especialista en Optimización Logística

- 🔬 **Expertise**: Python, SQL, Tableau, Power BI
- 📊 **Enfoque**: Transformar datos en decisiones estratégicas  
- 🎯 **Especialización**: Análisis operativo y optimización de procesos
- 💡 **Filosofía**: *"Los datos no mienten, pero hay que saber hacerles las preguntas correctas"*

### 🌐 Enlaces de Contacto

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/h0v4nn3ss)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](#)

## 🤝 Contribuciones

¿Tienes ideas para mejorar este análisis? ¡Las contribuciones son bienvenidas!

1. Fork el proyecto
2. Crea tu rama de feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`) 
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

---

<div align="center">

**⭐ Si este análisis te resultó útil, considera darle una estrella al repositorio ⭐**

**🔄 ¿Tienes datos similares? ¡Adaptemos este análisis a tu caso específico!**

Made with ❤️ and 📊 by [Andrés Ohannessian](https://github.com/h0v4nn3ss)

</div>yter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red.svg)](https://matplotlib.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📊 Descripción del Proyecto

Este proyecto presenta un análisis completo de optimización logística para una empresa textil, desarrollado como demostración de capacidades en **ciencia de datos aplicada a problemas empresariales reales**.

El análisis compara el modelo actual de despachos individuales contra un modelo propuesto de despachos agrupados dos veces por semana, utilizando técnicas de análisis de datos, modelado de costos y visualización avanzada.

## 🎯 Objetivo del Análisis

Evaluar la viabilidad de optimizar la estrategia logística mediante la agrupación de despachos, midiendo el impacto en:

- Reducción de costos de transporte
- Eficiencia operativa  
- Tiempos de entrega
- Consolidación de cargas

## 🚀 Demo Rápido

```python
# Resultados principales del análisis
Ahorro_Total = "$2,324,412 (92.9%)"
Reduccion_Viajes = "85 viajes menos (85.0%)"
Retraso_Promedio = "1.1 días"
ROI_Anual = "$2.3M"
```

## 📈 Resultados Principales

### 💰 Beneficios Cuantificados

- **Reducción de costos**: 92.9% de ahorro ($2,324,412 de $2,502,978 totales)
- **Eficiencia operativa**: 85.0% de reducción en viajes (de 100 a 15 viajes)
- **Impacto en servicio**: Retraso promedio de solo 1.1 días
- **Costo por viaje**: Reducción de $25,030 a $11,904 promedio por viaje

### 🗺️ Análisis por Zona Geográfica

| Zona | Ahorro (%) | Ahorro ($) | Reducción Viajes | Retraso (días) |
|------|------------|------------|------------------|----------------|
| Sur | 93.3% | $822,009 | 28 | 1.0 |
| Centro | 92.7% | $755,139 | 27 | 1.2 |
| Norte | 92.6% | $747,264 | 30 | 1.1 |
| **TOTAL** | **92.9%** | **$2,324,412** | **85** | **1.1** |

## � Características Técnicas

### 📊 Dataset
- **Registros**: 100 pedidos de enero 2024
- **Zonas geográficas**: 3 (Norte, Centro, Sur)
- **Tipos de cliente**: Minorista, Mayorista, Distribuidor
- **Variables**: ID, fechas, zona, peso, volumen, costo, tipo cliente, estado

### 🧮 Modelado de Costos
- **Costo fijo**: $10,000 por viaje
- **Costo variable**: $100 por cada 100kg
- **Frecuencia propuesta**: 2 despachos semanales por zona
- **Algoritmo**: Agrupación por zona y semana calendario

### 📈 Métricas de Evaluación
- Ahorro porcentual y absoluto
- Reducción de frecuencia de viajes
- Impacto en tiempos de entrega
- Eficiencia de consolidación de carga

## �📁 Estructura del Proyecto

```bash
textil-despachos/
│
├── 📓 analisis_optimizacion_logistica.ipynb    # Notebook principal con análisis completo
├── 📊 proyecto_textil_despachos.csv            # Dataset original con datos de despachos  
├── 📋 resumen_optimizacion_logistica.csv       # Tabla resumen ejecutiva generada
├── 📝 README.md                                 # Documentación del proyecto
└── 🔒 .gitignore                               # Archivos excluidos del repositorio
```

## 🛠️ Stack Tecnológico

| Tecnología | Propósito | Versión |
|------------|-----------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | Lenguaje principal | 3.8+ |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | Análisis de datos | Latest |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) | Cálculos numéricos | Latest |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white) | Visualización base | Latest |
| ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=python&logoColor=white) | Gráficos estadísticos | Latest |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) | Entorno interactivo | Latest |
- **Jupyter Notebook** - Entorno de desarrollo interactivo
## 🚀 Instalación y Ejecución

### ⚡ Inicio Rápido

```bash
# 1. Clonar el repositorio
git clone https://github.com/h0v4nn3ss/textil-despachos.git
cd textil-despachos

# 2. Instalar dependencias
pip install pandas numpy matplotlib seaborn jupyter

# 3. Lanzar Jupyter Notebook
jupyter notebook analisis_optimizacion_logistica.ipynb
```

### 🐳 Con Docker (Opcional)

```bash
# Ejecutar en contenedor
docker run -p 8888:8888 -v $(pwd):/home/jovyan jupyter/datascience-notebook
```

### 📋 Requisitos del Sistema

- **Python**: 3.8 o superior
- **RAM**: Mínimo 4GB recomendado
- **Espacio**: ~50MB para datos y notebooks
- **SO**: Windows, macOS, Linux

## 📊 Metodología de Análisis

### 🔍 1. Exploración de Datos (EDA)

- Carga y validación del dataset (100 pedidos, enero 2024)
- Análisis de distribución por zona, tipo de cliente y temporal
- Identificación de patrones y anomalías
- Estadísticas descriptivas y visualización inicial

### 🧮 2. Modelado de Escenarios

- **Escenario Baseline**: Un despacho individual por pedido
- **Escenario Optimizado**: Consolidación bi-semanal por zona
- Simulación de costos: componente fijo + variable por peso
- Modelado de impacto en tiempos de entrega

### ⚖️ 3. Análisis Comparativo

- Comparación cuantitativa de costos totales y por zona
- Evaluación del trade-off costo vs. tiempo de entrega
- Cálculo de métricas de eficiencia operativa
- Análisis de sensibilidad de parámetros

### 📊 4. Visualización y Reportes

- Dashboard interactivo con gráficos comparativos
- Análisis temporal de volúmenes y costos
- Heatmaps de distribución geográfica
- Tabla ejecutiva para toma de decisiones

## 🚀 Cómo Ejecutar el Análisis

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/h0v4nn3ss/textil-despachos.git
   cd textil-despachos
   ```

2. **Instalar dependencias**:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Ejecutar el notebook**:

   ```bash
   jupyter notebook analisis_optimizacion_logistica.ipynb
   ```

## 💡 Insights Clave

1. **Oportunidad significativa**: El ahorro del 92.9% indica una oportunidad masiva de optimización
2. **Balance servicio-costo**: El retraso promedio de 1.1 días es aceptable para el nivel de ahorro
3. **Consistencia geográfica**: Todas las zonas muestran ahorros similares (92.6% - 93.3%)
4. **Escalabilidad**: El modelo se mantiene eficiente a lo largo del período analizado

## 📊 Recomendaciones

### Plan de Implementación

1. **Fase Piloto (Mes 1)**: Iniciar con zona Sur (mayor ahorro: 93.3%)
2. **Escalamiento (Mes 2-3)**: Incorporar Centro y Norte progresivamente
3. **Optimización (Mes 4+)**: Ajustar frecuencias según demanda estacional

### Consideraciones Estratégicas

- Comunicación clara con clientes sobre nuevos tiempos de entrega
- Mantener opción de despacho express para clientes premium
- Monitoreo continuo de KPIs de costo y satisfacción
- Evaluación de capacidad de almacenamiento temporal

## 👨‍💻 Perfil Profesional

Proyecto desarrollado por **Andrés Ohannessian**, analista de datos en formación con enfoque en estructuración, limpieza y optimización de procesos.

- **Herramientas favoritas:** Python, SQL, Tableau.
- **Lema profesional:** “Ordena y entenderás”.