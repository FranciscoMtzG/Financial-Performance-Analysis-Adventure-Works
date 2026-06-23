# 💰 Análisis del Desempeño Financiero de AdventureWorks con SQL

## 📊 Introducción
Analisi para identificar **los mercados con mayor ingreso y rentabilidad** para decidir dónde invertir el próximo dólar de marketing.

Con datos de órdenes, productos, territorios y campañas, la asignacion es **priorizar mercados**, **optimizar presupuesto** y **evaluar rentabilidad**.

---

### Tablas Disponibles
Usaremos un subconjunto del dataset de **AdventureWorks**:

- **ventas_2017** → Transacciones de líneas de pedido (2017).  
  Grano: una línea por producto y pedido.  
- **productos** → Catálogo con atributos, costo y precio unitario por `ClaveProducto`.  
- **productos_categorias** → Jerarquía categoría/subcategoría para enriquecer productos.  
- **clientes** → Maestro de clientes con segmento y ubicación.  
- **territorios** → Mapa de `ClaveTerritorio` → país y continente.  
- **campanas** → Gasto de marketing por territorio/campaña.

---

## 💼 Contexto del Negocio
El director financiero busca responder dos preguntas clave:

1. **¿Cuánto estamos ganando por país?**  
2. **¿Qué tan rentable es cada mercado considerando los gastos de marketing?**

El análisis permitirá:
- Identificar mercados más rentables.  
- Detectar oportunidades de optimización de presupuesto.  
- Priorizar territorios con mejor relación entre ingresos, margen y gasto en campañas.

---

## 🔍 Metodología

- Navegar un esquema relacional y usar  **JOINs** para combinar tablas.  
- Extraer, filtrar y limpiar datos con SQL (manejo de **NULLs**, **casting de tipos**, estandarización de categorías).  
- Calcular indicadores financieros clave: **ingresos, costos, beneficio bruto, margen y ROI**.  
- Validar y controlar calidad (**QA**) con comprobaciones de totales y márgenes.  
- Redactar un informe ejecutivo con visualizaciones usando el método **Contexto → Hallazgo → Implicación (C→F→I)**.
---

## 🛠️ Herramientas Utilizadas
- **SQL** (consultas, vistas y cálculos financieros)  
- **Google Drive / Excel** (resumen ejecutivo y visualizaciones)  
- **AdventureWorks Dataset**

---

## 📈 Resultados Esperados
- Ranking de países por ingresos y rentabilidad.  
- Identificación de mercados con ROI positivo.  
- Recomendaciones para optimizar inversión en marketing.  
- Informe ejecutivo con hallazgos clave y visualizaciones.
