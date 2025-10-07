# Análisis de Optimización Logística: Despachos Textiles

## 📊 Descripción del Proyecto

Este proyecto presenta un análisis completo de optimización logística para una empresa textil, comparando el modelo actual de despachos individuales contra un modelo propuesto de despachos agrupados dos veces por semana por zona geográfica.

## 🎯 Objetivo del Análisis

Evaluar la viabilidad de optimizar la estrategia logística mediante la agrupación de despachos, midiendo el impacto en:
- Reducción de costos de transporte
- Eficiencia operativa
- Tiempos de entrega
- Consolidación de cargas

## 📈 Resultados Principales

### Beneficios Cuantificados
- **Reducción de costos**: 92.9% de ahorro ($2,324,412 de $2,502,978 totales)
- **Eficiencia operativa**: 85.0% de reducción en viajes (de 100 a 15 viajes)
- **Impacto en servicio**: Retraso promedio de solo 1.1 días
- **Costo por viaje**: Reducción de $25,030 a $11,904 promedio por viaje

### Análisis por Zona Geográfica
| Zona | Ahorro (%) | Ahorro ($) | Reducción Viajes | Retraso (días) |
|------|------------|------------|------------------|----------------|
| Sur | 93.3% | $822,009 | 28 | 1.0 |
| Centro | 92.7% | $755,139 | 27 | 1.2 |
| Norte | 92.6% | $747,264 | 30 | 1.1 |
| **TOTAL** | **92.9%** | **$2,324,412** | **85** | **1.1** |

## 📁 Estructura del Proyecto

```
textil-despachos/
│
├── analisis_optimizacion_logistica.ipynb    # Notebook principal con análisis completo
├── proyecto_textil_despachos.csv            # Dataset original con datos de despachos
├── resumen_optimizacion_logistica.csv       # Tabla resumen ejecutiva generada
├── README.md                                 # Documentación del proyecto
└── .gitignore                               # Archivos excluidos del repositorio
```

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Cálculos numéricos
- **Matplotlib** - Visualización de datos
- **Seaborn** - Gráficos estadísticos
- **Jupyter Notebook** - Entorno de desarrollo interactivo

## 📋 Metodología

### 1. Análisis Exploratorio
- Carga y exploración del dataset (100 pedidos, enero 2024)
- Análisis de distribución por zona, tipo de cliente y temporal
- Identificación de patrones y tendencias

### 2. Modelado de Escenarios
- **Escenario Actual**: Un despacho por pedido
- **Escenario Propuesto**: Despachos agrupados dos veces por semana
- Cálculo de costos: fijo ($10,000/viaje) + variable ($100/100kg)

### 3. Análisis Comparativo
- Comparación de costos totales y por zona
- Evaluación del impacto en tiempos de entrega
- Cálculo de métricas de eficiencia operativa

### 4. Visualización y Reportes
- Gráficos comparativos de costos y viajes
- Distribución de retrasos y evolución temporal
- Tabla resumen ejecutiva para toma de decisiones

## 🚀 Cómo Ejecutar el Análisis

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/textil-despachos.git
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

## 👤 Autor

Análisis desarrollado como demostración de capacidades en ciencia de datos aplicada a optimización logística.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

**¿Tienes preguntas sobre el análisis?** No dudes en abrir un issue o contactar directamente.