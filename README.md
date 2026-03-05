# 🛒 Challenge Data Science — AluraStore Latam

Análisis exploratorio de datos de cuatro tiendas del Sr. João para determinar cuál debería vender, basado en métricas clave de rendimiento comercial.

---

## 📋 Descripción del Proyecto

Este proyecto forma parte del **Challenge 1 de Data Science de Alura Latam**. El objetivo es analizar los datos de ventas de cuatro tiendas y, a través de visualizaciones y métricas, emitir una recomendación fundamentada sobre cuál tienda conviene vender.

---

## 🎯 Objetivos

- Analizar la **facturación total** de cada tienda
- Identificar las **categorías de productos más populares**
- Evaluar el **promedio de calificación** de los clientes
- Determinar los **productos más y menos vendidos**
- Comparar el **costo promedio de envío** entre tiendas
- Emitir una **recomendación final** basada en los datos

---

## 📁 Estructura del Proyecto

```
challenge-alurastore/
│
├── AluraStoreLatam.ipynb   # Notebook principal con el análisis completo
└── README.md               # Este archivo
```

---

## 📊 Análisis Realizados

### 1. 💰 Facturación Total por Tienda
Gráfico de barras comparando los ingresos totales generados por cada tienda, con etiquetas de valor sobre cada barra.

### 2. 🛒 Categorías Más Populares
Gráficos circulares (pie charts) por tienda mostrando la distribución de ventas según la categoría del producto.

### 3. ⭐ Calificación Promedio de Clientes
Gráfico de barras horizontales con el promedio de calificación (escala 1–5) que los clientes asignaron a cada tienda.

### 4. 📦 Productos Más y Menos Vendidos
Comparativa side-by-side del Top 10 productos más vendidos vs. los 10 menos vendidos en el total de las tiendas.

### 5. 🚚 Costo Promedio de Envío
Gráfico de barras resaltando la tienda con menor costo (verde) y mayor costo (rojo) de envío.

### 6. 🔍 Dispersión: Precio vs Calificación
Scatter plot comparando el precio de los productos contra la calificación recibida, segmentado por tienda.

### 7. 🗺️ Mapa de Calor de Ventas por Categoría
Heatmap construido con Seaborn que cruza tienda vs. categoría del producto para visualizar dónde se concentran las ventas.

---

## 🛠️ Tecnologías Utilizadas

| Librería | Uso |
|----------|-----|
| `pandas` | Carga, limpieza y análisis de datos |
| `matplotlib` | Visualizaciones principales |
| `seaborn` | Mapa de calor |
| `numpy` | Operaciones numéricas auxiliares |

---

## ▶️ Cómo Ejecutar

1. Abre el archivo `AluraStoreLatam.ipynb` en [Google Colab](https://colab.research.google.com/)
2. Ejecuta las celdas en orden (Entorno de ejecución → Ejecutar todo)
3. No es necesario instalar dependencias adicionales, todas las librerías están disponibles en Colab por defecto

---

## 🗃️ Fuente de Datos

Los datos fueron provistos por Alura Latam y se cargan directamente desde su repositorio oficial en GitHub:

| Tienda | URL |
|--------|-----|
| Tienda 1 | `challenge1-data-science-latam/.../tienda_1.csv` |
| Tienda 2 | `challenge1-data-science-latam/.../tienda_2.csv` |
| Tienda 3 | `challenge1-data-science-latam/.../tienda_3.csv` |
| Tienda 4 | `challenge1-data-science-latam/.../tienda_4.csv` |

Cada dataset contiene las columnas: `Producto`, `Categoría del Producto`, `Precio`, `Costo de envío`, `Fecha de Compra`, `Vendedor`, `Lugar de Compra`, `Calificación`, `Método de pago`, `Cantidad de cuotas`, `lat`, `lon`.

---

## 📝 Recomendación Final

Después de evaluar las cuatro tiendas en todas las métricas analizadas, se identificó la tienda con menor facturación, peor calificación promedio de clientes, mayor costo de envío y menor volumen de ventas.

> **Conclusión:** Se recomienda al Sr. João vender la tienda con peor desempeño acumulado, concentrando sus recursos e inversión en las tiendas con mayor rentabilidad y satisfacción del cliente. El detalle completo de la recomendación se encuentra al final del notebook.

---

## 👤 Autor

Desarrollado como parte del programa de formación en Data Science de **Alura Latam**.
