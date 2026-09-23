# Market Basket Analysis y Patrones de Compra en un E-commerce Saludable

## Sobre la empresa
Sano & Fresco es una tienda online de alimentos saludables que ha crecido mucho en los últimos años. Sin embargo, en los últimos meses ha notado una baja en sus ventas.

Para solucionar esto, necesitamos:

- Analizar las ventas para descubrir exactamente qué está pasando.

- Diseñar un tablero visual (dashboard) que nos permita ver los resultados de forma rápida y clara.

- Proponer una solución práctica para recuperar a los clientes y subir las ventas otra vez.

<img width="1890" height="838" alt="image" src="https://github.com/user-attachments/assets/7fd00855-ef2e-4d6a-ba83-3d1634b8b605" />

## Objetivos del Proyecto
- a. Analizar los datos para entender las ventas
- b. Diseñar un cuadro de mando (Dashboard)
- c. Diseñar un algoritmo en python basado en Market Basket Analysis

## Estructura del Proyecto
<img width="657" height="378" alt="image" src="https://github.com/user-attachments/assets/b8200530-fe33-406c-88d2-9837784a350b" />

---

## 🚀 Pasos y Fases del Proyecto

### Fase 1: Extracción de Datos y SQL (`/sql` y `/data`)
* **Base de datos (`base de datos.db`):** Contiene la información transaccional de los clientes, productos y pedidos.
* **Consultas:** En la carpeta `sql/` encontrarás los scripts utilizados para agrupar ventas por mes, categoría y cliente.
* **💡 Principales Insights:**
  * Se identificó que la caída de ventas se concentra principalmente en la categoría de snacks, coincidiendo con una pérdida de recompra.
  * Los clientes antiguos han reducido su frecuencia de compra mensual en un 20%.

### Fase 2: Dashboard General de Ventas (`/dashboards`)
* Un tablero visual diseñado para monitorear el comportamiento de las ventas mes a mes.
* **Objetivo:** Permitir a la gerencia ver de forma rápida qué productos y regiones son los más afectados por la baja reciente.

### Fase 3: Market Basket Analysis con Python (`/notebooks`)
* **Código de Python:** Se implementó un algoritmo de análisis de asociación en la libreta `market_basket_analysis.ipynb`.
* **Hallazgo clave:** Descubrimos qué productos suelen comprarse juntos (ej. verduras con aderezos saludables). Esto permitió diseñar estrategias de venta cruzada (cross-selling) para recuperar el ticket promedio.
* **Dashboard del Carrito:** Visualización específica que muestra las combinaciones de productos más populares para optimizar las ofertas de la tienda.

---

## 🛠️ Herramientas y Tecnologías
* **SQL:** Extracción y limpieza inicial de datos.
* **Python (Pandas, Mlxtend):** Ejecución del Market Basket Analysis.
* **Herramienta de Dashboard:** [PowerBI / Tableau / Looker Studio] *(indica cuál usaste)*.

---

