# Alura Store LATAM - Proyecto Data Science

Este repositorio contiene el desarrollo del primer challenge del programa **Oracle Next Education - Data Science** realizado con Python. El proyecto analiza datos de ventas de 4 tiendas ficticias con el objetivo de identificar la mejor opción para vender productos del Sr. Juan.

---

## 📊 Objetivo del Proyecto

Analizar diferentes dimensiones de datos para responder a la pregunta:

> ¿A cuál tienda debería vender el Sr. Juan sus productos?

## 🗂️ Estructura del Análisis

El análisis se desarrolló en 5 secciones clave:

1. **Ingreso Total por Tienda**  
   Se calculó el total de ingresos por tienda y se visualizó mediante un gráfico de barras.

2. **Ventas por Categoría**  
   Se analizaron las categorías de productos más vendidas, con apoyo de gráficos de barras y barras apiladas.

3. **Valoración Promedio por Tienda**  
   Se calculó el promedio de calificaciones otorgadas por los clientes a cada tienda, visualizado con gráficos de barra y torta.

4. **Productos Más y Menos Vendidos**  
   Se identificaron los productos más y menos vendidos en cada tienda y se representaron gráficamente.

5. **Valor de Envío Promedio por Tienda**  
   Se analizó el costo promedio de envío por tienda mediante gráficos de barra y de líneas.

Finalmente, se presenta un **informe ejecutivo** con conclusiones basadas en todos los análisis anteriores.

---

## 🚷 Estructura del Proyecto

```bash
.
├── CH_AnalisisTienda.ipynb      # Notebook principal del análisis
├── README.md                    # Este archivo
├── base-de-datos-challenge1-latam
    ├── tienda_1.csv                 # Datos de la Tienda 1
    ├── tienda_2.csv                 # Datos de la Tienda 2
    ├── tienda_3.csv                 # Datos de la Tienda 3
    ├── tienda_4.csv                 # Datos de la Tienda 4

```

---

## ⚖️ Tecnologías Utilizadas

* Python 3.11+
* Pandas
* Matplotlib
* Google Colab
* Seaborn

---

## 📦 Instalación y Ejecución

1. Clona este repositorio:

```bash
git clone https://github.com/PamelaOrmeno/challenge-analisis-negocio.git
```

2. Accede al entorno:

```bash
cd challenge-analisis-negocio
```

3. Instala dependencias (si usas entorno local):

```bash
pip install pandas matplotlib
```

4. Abre el notebook en Jupyter o Google Colab:

* [Google Colab](https://colab.research.google.com/)

---

## 🚫 Posibles Problemas

* ❌ **Error de red al cargar desde GitHub**: si estás sin conexión, usa los CSV locales directamente.
* ⚠️ **Faltan columnas esperadas**: asegúrate de que los archivos CSV originales no hayan sido modificados.

---

## 📄 Conclusión

El análisis completo se encuentra en el archivo [`CH_AnalisisTienda.ipynb`](./CH_AnalisisTienda.ipynb), incluyendo un informe ejecutivo final con visualizaciones y recomendaciones para decidir a qué tienda debería vender Don Juan sus productos, basado en datos de ingresos, categorías más vendidas, valoraciones, stock y costos de envío.


---

## 📚 Recursos

* [Alura - Programa Oracle Next Education](https://www.aluracursos.com/)
* [Artículo sobre cómo crear un README increíble](https://www.aluracursos.com/blog/como-escribir-un-readme-increible-en-tu-github)

---

👩‍💻 Autora
[Pamela Ormeño](https://linkedin.com/in/pamelaormeno)

🚀 *Proyecto realizado como parte del reto de formación en Ciencia de Datos*
