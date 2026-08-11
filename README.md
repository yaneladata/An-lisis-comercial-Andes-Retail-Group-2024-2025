# An-lisis-comercial-Andes-Retail-Group-2024-2025
Análisis de datos comerciales del Grupo 2024 realizado en Tableau, enfocado en ventas, productos , clientes y principales indicadores para identificar tendencias y oportunidades de negocio..
# 📊 Andes Retail Group - Dashboard Comercial Interactivo

**Proyecto de portafolio:** Dashboard ejecutivo en Tableau para análisis de desempeño comercial 2024-2025

## 📋 Descripción del Proyecto

Dashboard interactivo que analiza el desempeño comercial de **Grupo Comercial Andes**, una empresa de retail con operaciones en **Perú, Chile y Colombia**. 

El proyecto responde **6 preguntas de negocio clave** a través de **2 dashboards integrados** (síntesis ejecutiva + análisis detallado) con **filtros interactivos** y análisis temporal comparativo.

---

## 🎯 Preguntas de Negocio Respondidas

1. ✅ **¿Cómo evolucionan los ingresos 2024 vs 2025?**
   - Comparativa de crecimiento año a año
   - Identificación de meses críticos

2. ✅ **¿Qué segmentos generan mayor ingreso/rentabilidad?**
   - Análisis por segmento de cliente
   - Margen de ganancia por segmento

3. ✅ **¿Qué categorías tienen mayor impacto comercial?**
   - Participación de Electrónica, Ropa, Deportes, Hogar
   - Análisis de ingresos vs unidades vendidas

4. ✅ **¿Cuáles son las diferencias entre países y regiones?**
   - Rentabilidad geográfica
   - Oportunidades de mejora por país

5. ✅ **¿Existen patrones temporales/estacionales?**
   - Análisis de estacionalidad por clima
   - Variación de rentabilidad por estación

6. ✅ **¿Cuáles son las oportunidades de mejora?**
   - Diagnóstico: ingresos vs margen
   - Identificación de segmentos/países suboptimizados

---

## 📊 Estructura del Dashboard

### 📈 **Dashboard 1: Vista Overview (Síntesis Ejecutiva)**

**Propósito:** Lectura rápida en segundos, ideal para ejecutivos

**Contenidos:**
- **4 KPIs Principales**
  - Ingresos Totales (2024-2025)
  - Unidades Vendidas
  - Ganancia Total
  - % Margen de Ganancia

- **4 Visualizaciones Clave**
  - Evolución Ingresos (Línea 2024 vs 2025)
  - Impacto de Categorías (Barras participación)
  - Ingresos/Ganancia por Segmento (Análisis comparativo)
  - Oportunidades por País-Región (Diagnóstico)

- **Filtros Interactivos**
  - Año (2024, 2025, Todo)
  - País (Perú, Chile, Colombia)
  - Categoría (Electrónica, Ropa, Deportes, Hogar)
  - Segmento de Cliente

---

### 🔍 **Dashboard 2: Vista Detalle (Análisis Profundo)**

**Propósito:** Diagnóstico detallado para análisis estratégico

**Contenidos:**
- **5 Análisis Especializados**
  1. Estacionalidad por Clima
     - Verano, Invierno, Primavera, Otoño
     - Rentabilidad por estación
  
  2. Rentabilidad por Estación y Categoría
     - Matriz: Estación × Categoría
     - Identificar picos y valles
  
  3. Rentabilidad Geográfica
     - Comparativa País-Región por Categoría
     - Margen por zona
  
  4. Scatter Diagnóstico
     - Eje X: Ingresos
     - Eje Y: Margen
     - Burbuja: Segmento/Categoría
  
  5. Tabla Comparativa
     - País, Región, Categoría, Segmento
     - Métricas: Ingresos, Unidades, Margen %

- **Filtros Interactivos**
  - Mes
  - País
  - Categoría
  - Estación

---

## 📈 Métricas Clave

| Métrica | Observación |
|---------|-------------|
| Ingresos Totales | Crecimiento YoY positivo 2024-2025 |
| Margen de Ganancia | Consistente ~34.8%-35.5% entre cortes |
| Categoría Top | Electrónica (mayor ingresos) |
| País Principal | Colombia (operación concentrada) |
| Segmento Premium | Corporativo (mayor margen) |

---

## 🛠️ Stack Tecnológico

- **Herramienta BI:** Tableau Desktop / Tableau Public
- **Datos:** Dataset transaccional (CSV/Excel)
- **Lenguaje de Análisis:** Tableau Calculated Fields
- **Documentación:** Markdown, SCQA Narrative



---

## 📊 Datos del Proyecto

**Período:** Enero 2024 - Diciembre 2025  
**Registros:** ~10,000 transacciones  
**Granularidad:** Transacción individual  

**Dimensiones:**
- Geográfica: Perú, Chile, Colombia
- Temporal: Estaciones climáticas
- Comercial: 4 categorías de producto
- Cliente: 3 segmentos

---

## 🔑 Insights Principales

### 📈 Crecimiento 2025 vs 2024
- ✅ Ingresos en línea de crecimiento positivo
- ✅ Consistencia en margen de ganancia
- ⚠️ Variación estacional identificada

### 🏆 Categoría Ganadora
- **Electrónica:** Mayor participación de ingresos
- **Ropa:** Volumen consistente
- **Deportes y Hogar:** Nicho especializado

### 🌍 Desempeño Geográfico
- **Colombia:** Operación principal
- **Perú y Chile:** Oportunidades de expansión
- **Margen similar:** 34.8%-35.5% entre países

### 👥 Segmentación de Clientes
- **Corporativo:** Mayor margen de ganancia
- **Consumidor:** Mayor volumen
- **PyME:** Crecimiento potencial

---

## 💡 Oportunidades Identificadas

1. **Expansión Geográfica**
   - Aumentar presencia en Perú y Chile
   - Replicar modelo de Colombia

2. **Optimización de Categorías**
   - Potenciar Deportes en verano
   - Mejorar mix de productos

3. **Segmentación de Clientes**
   - Desarrollar ofertas corporativas
   - Retención de cliente de alto margen

4. **Estacionalidad**
   - Planificación de inventario por estación
   - Campañas temáticas

---

## 🎓 Metodología

**Enfoque SCQA** para narrativa ejecutiva clara
**Cálculos utilizados:**
- Margen: (Ingresos - Costo) / Ingresos × 100
- Participación: Categoría / Total × 100
- YoY: (2025 - 2024) / 2024 × 100

---

## 📌 Cómo Usar los Dashboards

**Overview (Ejecutivos):**
1. Abre Vista_Overview.twbx
2. Observa KPIs principales (30 seg)
3. Filtra por País/Categoría si necesitas
4. Identifica tendencias generales

**Detalle (Análisis):**
1. Abre Vista_Detalle.twbx
2. Examina estacionalidad
3. Usa scatter para diagnóstico
4. Compara con tabla
5. Define acciones

---


## 🎯 Conclusión

Este dashboard demuestra:
- ✅ **Capacidad analítica:** Análisis multidimensional
- ✅ **Storytelling:** Narrativa ejecutiva
- ✅ **UX/Design:** Interfaz profesional
- ✅ **Business Acumen:** Preguntas correctas

