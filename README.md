# Challenge-Que-Tienda-Vender
# 🛒 Análisis de Evasión de Clientes y Rendimiento de Tiendas

Este proyecto tiene como objetivo realizar un análisis consolidado de datos de ventas provenientes de cuatro tiendas distintas, con el fin de identificar patrones de comportamiento de los clientes, determinar el rendimiento por tienda y formular recomendaciones basadas en datos.

---

## 🎯 Propósito del Análisis

- Identificar los factores clave que influyen en la evasión de clientes.
- Analizar el rendimiento de cada tienda a partir de sus ventas, calificaciones y costos asociados.
- Proporcionar al Sr. Juan una recomendación fundamentada sobre cuál tienda tiene mejor desempeño general.

---

## 🔍 Metodología del Análisis

### 📥 1. Importación y Unión de Datos

- Se cargaron los datos de las **cuatro tiendas** en DataFrames separados.
- Posteriormente, se **unieron en un único DataFrame** para facilitar el análisis consolidado.

### 💰 2. Cálculo de Facturación por Tienda

- Se calculó la **facturación total** de cada tienda multiplicando el precio del producto por la cantidad de cuotas vendidas.

### 🗃️ 3. Análisis de Ventas por Categoría

- Los datos se agruparon por **categoría de producto** para obtener la cantidad total de ventas por tipo de producto.

### ⭐ 4. Determinación de la Calificación Promedio

- Se calculó la **calificación promedio de los clientes** para cada tienda, como indicador de satisfacción.

### 🛍️ 5. Identificación de Productos Más y Menos Vendidos

- Se determinaron los productos **más y menos vendidos** basándose en la cantidad total de unidades comercializadas.

### 🚚 6. Cálculo del Costo de Envío Promedio

- Se calculó el **costo de envío promedio** por tienda, permitiendo evaluar la eficiencia logística.

### 📊 7. Visualización de Resultados

- Se generaron diversos **gráficos de barras** para visualizar los hallazgos clave:
  - Facturación total por tienda.
  - Ventas por categoría de producto.
  - Calificación promedio por tienda.
  - Costo de envío promedio por tienda.

### 🧾 8. Elaboración del Informe Final

- Se sintetizó toda la información en un informe final, incluyendo:
  - Hallazgos clave.
  - Visualizaciones.
  - Una **recomendación justificada** sobre cuál tienda es más conveniente para que el Sr. Juan continúe vendiendo.

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.7+**
- **Pandas** – Manipulación de datos
- **Matplotlib & Seaborn** – Visualización de datos
- **Jupyter Notebook** – Desarrollo interactivo

---

## ⚙️ Instrucciones para Ejecutar el Notebook

1. Asegurate de tener Python instalado (versión 3.7 o superior).
2. Instala las dependencias necesarias:

```bash
pip install pandas matplotlib seaborn
