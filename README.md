# 🛍️ Análisis de Rendimiento de Tiendas - Challenge Data Science LATAM

Este proyecto tiene como objetivo analizar el desempeño de **cuatro tiendas online** con base en datos de ventas, calificaciones de clientes, categorías de productos, costos de envío y más. El análisis fue realizado como parte del **Challenge de Data Science de Alura LATAM**.

---

## 📂 Contenido

1. [Importación de Datos](#importación-de-datos)
2. [Análisis de Facturación Total](#1-análisis-de-facturación)
3. [Ventas por Categoría de Producto](#2-ventas-por-categoría)
4. [Calificación Promedio por Tienda](#3-calificación-promedio-de-la-tienda)
5. [Productos Más y Menos Vendidos](#4-productos-más-y-menos-vendidos)
6. [Costo de Envío Promedio](#5-envío-promedio-por-tienda)
7. [Conclusión y Recomendación Final](#conclusión)

---

## 📥 Importación de Datos

Se utilizan archivos CSV públicos disponibles en GitHub, correspondientes a las cuatro tiendas evaluadas:

- Tienda 1
- Tienda 2
- Tienda 3
- Tienda 4

Los datos se cargan usando la librería `pandas`.

---

## 1️⃣ Análisis de Facturación

Se calcula el **ingreso total por tienda** sumando los valores de la columna `Precio`. Se visualiza con una gráfica de barras comparativa.

📊 **Resultado:**  
La tienda con mayor facturación es **Tienda 1**, seguida por la Tienda 2.

---

## 2️⃣ Ventas por Categoría

Se agrupan las ventas por la columna `Categoría del Producto` para cada tienda.  
Esto permite identificar qué tipo de producto genera mayores ingresos en cada tienda.

🎯 **Insight:**  
Las categorías de tecnología y hogar son líderes en ventas según la tienda.

---

## 3️⃣ Calificación Promedio de la Tienda

Se calcula el promedio de la columna `Calificación` para cada tienda y se grafica en formato de radar y barra.

🌟 **Mejor calificación:**  
**Tienda 3**, lo que sugiere alta satisfacción del cliente.

---

## 4️⃣ Productos Más y Menos Vendidos

Se contabiliza la cantidad de ventas por producto (por número de filas o sumando las cuotas), y se grafican en orden.

🔥 **Más vendidos:**  
Se destacan productos específicos que podrían representar una ventaja competitiva.

---

## 5️⃣ Envío Promedio por Tienda

Se analiza el costo medio de envío de cada tienda usando la columna `Costo de envío`.

💸 **Tienda con menor costo de envío:**  
**Tienda 3**, lo que podría mejorar la conversión en ventas.

---

## ✅ Conclusión

Después del análisis de todos los factores, se recomienda al **Sr. Juan** elegir la **Tienda 3** para vender sus productos por las siguientes razones:

- ⭐ **Mejor calificación promedio**
- 📦 **Costo de envío más bajo**
- 🛒 **Demanda sólida en productos clave**

Tienda 3 destaca como una opción eficiente y confiable para maximizar ventas y reputación.

---

## 🧰 Tecnologías Utilizadas

- Python 3.x
- Pandas
- Matplotlib
- Numpy
- Jupyter Notebook

---

## 📌 Autor

**Desarrollado por:** *[Tu Nombre Aquí]*  
Challenge Data Science - Alura LATAM

---

## 📎 Recomendaciones Futuras

- Incluir análisis temporal (si se dispone de fechas)
- Crear dashboards interactivos con Plotly o Power BI
- Estimar rentabilidad real por producto/categoría

