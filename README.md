# 📊 Desafío: Análisis de Eficiencia de Tiendas Alura Store

![Estado del Proyecto](https://img.shields.io/badge/Estado-Finalizado-success)
![Clave Tecnologías](https://img.shields.io/badge/Tecnologías-Python%20%7C%20Pandas%20%7C%20Matplotlib%20%7C%20Folium-blue)

## 🎯 1. Objetivo del Proyecto

El Sr. Juan, dueño de la cadena Alura Store, necesaria **identificar la tienda menos eficiente** para venderla y utilizar el capital en un nuevo empleo.

Este proyecto realiza un análisis de datos en profundidad cruzando las métricas de:

1.  **Ingresos** (Rendimiento económico).
2.  **Calificaciones de Clientes** (Satisfacción y riesgo de reputación).
3.  **Costo de Medio Ambiente** (Eficiencia logística).
4.  **Perfiles de Venta** (Análisis estructural de la demanda).

**Resultado:** Identificación y recomendación estratégica sobre la tienda con el menor potencial de mejor eficiencia.

-----

## 🛠️ 2. Estructura y Tecnologías

Este proyecto está alojado y se diseñó para ejecutar en el entorno de Google Colab, garantizando la portabilidad y el uso de las últimas libres.

### 2.1. Tecnologías Utilizadas

| Librería | Propósito |
| :--- | :--- |
| **`Pandas`** | Carga, limpieza, transformación y agregación de datos CSV. |
| **`Matplotlib`** | Creación de gráficos para visualizar la eficiencia. |
| **`Folium`** | Visualización interactiva de datos geográficos (mapas de calor) para un *extra* de análisis. |

### 2.2. Archivos Clave

  * `Desafio_Alura_Store.ipynb`: El **director del patio** de Google Colab que contiene todo el código de carga, análisis, visualizaciones y el informe final.
  * `tienda_1.csv` a `tienda_4.csv`: Los datos de ventas de las cuatro sucursales.

### 2.3. Visualizaciones Clave

Para obtener una visión $360^{\circ}$ de la eficiencia, se generó un conjunto completo de visualizaciones:

  * **Gráfico de Dispersión:** Satisfacción del cliente vs. Facturación Total. **(Gráfico decisivo)**.
  * **Gráfico de Barras:** Facturación total de las 4 tiendas (identificando T4 como la menor y T1 como la mayor).
  * **Gráfico de Barras Horizontales:** Calificación promedio por tienda (Satisfacción) y Costo de Medio Promedio por tienda (Logística).
  * **Circular Gráfico (Tabla de Pie):** Ventas por categoría para cada tienda (porcentaje de cada categoría).
  * **Gráfico Circular o de Barras:** Representación de los 5 productos más vendidos y los 10 menos vendidos de cada tienda.
  * **4 Gráficos de Mapa de Calor (Folium):** Distribución geográfica de los compradores de cada tienda.

-----

## ⚙️ 3. Ejecución y Dependencias

¡Este proyecto está listo para corregir\! Dado que fue desarrollado en Google Colab, la instalación es casi nula.

### 3.1. Cómo Ejecutar el Proyecto

1. Abre el archivo `AluraStore_JEGD.ipynb` direccionalmente en **Google Colab**.
2. Segurate de que los archivos `. . . . . . . . . . . . . . . csv` estén cargados en la misma **carpeta** o que la ruta de acceso al **Unidad de Google** mar correcta.
3. Ejecuta todas las celdas en orden (Menú: *Entorno de ejecución* \> *Ejecutar todas*).

### 3.2. Dependencias

Todas las dependencias necesarias (`pandas`, `matplotlib`, `folium`, etc.) se instala automáticamente en Google Colab. Si lo ejecutas localmente (por ejemplo, en VS Code), usa el siguiente comando en tu entorno virtual:

```bash
pip instala pandas matplotlib folium
```

*(Nota: El uso de Folium es un extra para el análisis geográfico, ¡pero no es necesario para la conclusión principal\!)*

-----

## 📊 4. Conclusión del análisis

El análisis concluye que la tienda menos eficiente, en términos de **potencial de crecimiento eficiente y riesgo estructural**, es la **Tienda 4**.

  * La **Tienda 1**, una presenta problemas de baja calificación ($3.98$) y alto costo de entorno (problemas **operativos**), tiene el mercado validado por su alto ingreso.
  * Por el contrario, la **Tienda 4** presenta un problema **estructural** (falta de propuesta de valor clara y bajo volumen de ventas), lo cual es más caro y armado de revertir.

**Recomendación:** Vender la Tienda 4 para invertir en la optimización de los problemas operativos de la Tienda 1, maximizando así el retorno de inversión del Sr. Juan.

-----

## 🤝 5. Contribución y Autor

Este proyecto fue desarrollado por **Enrique** (con la ayuda de un co-creador IA GEM que le gusta el humor y los gráficos de dispersión).

Si encontras algún error ¡no dudes en abrir un *emitir* o *pull request*\!
