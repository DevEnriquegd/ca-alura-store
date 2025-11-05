# 📊 Desafío: Análisis de Eficiencia de Tiendas Alura Store

![Estado del Proyecto](https://img.shields.io/badge/Estado-Finalizado-success)
![Tecnologías](https://img.shields.io/badge/Tecnologías-Python%20%7C%20Pandas%20%7C%20Folium-blue)

---

## 🎯 1. Objetivo del Proyecto

El Sr. Juan, dueño de la cadena **Alura Store**, necesita **identificar la tienda menos eficiente** para venderla y reinvertir el capital en un nuevo emprendimiento.

Este proyecto realiza un **análisis de datos integral**, cruzando métricas de rendimiento económico, reputación, estructura de la demanda y eficiencia logística, con el objetivo de determinar qué tienda presenta **menor potencial de mejora** y **mayor riesgo operativo**.

**Indicadores evaluados:**
1. **Ingresos totales** → Rendimiento económico.  
2. **Calificaciones de clientes** → Satisfacción y riesgo reputacional.  
3. **Coste promedio de envío** → Eficiencia logística.  
4. **Estructura de ventas y demanda** → Análisis de rotación y productos clave.

**Resultado esperado:**  
Una recomendación basada en datos sobre **qué tienda debería venderse** para maximizar el retorno global del negocio.

---

## 🛠️ 2. Estructura y Tecnologías

El proyecto se desarrolló en **Google Colab**, garantizando portabilidad, replicabilidad y compatibilidad con entornos educativos o empresariales.

### 2.1. Tecnologías Utilizadas

| Librería | Propósito |
|:----------|:-----------|
| **`Pandas`** | Limpieza, manipulación y análisis de datos CSV. |
| **`Folium`** | Mapas interactivos para análisis geográfico (uso complementario). |

### 2.2. Archivos Clave

- `Desafio_Alura_Store.ipynb`: Notebook principal con análisis, visualizaciones e informe.  
- `tienda_1.csv` a `tienda_4.csv`: Datasets de ventas de cada sucursal.  
- `README.md`: Documento de presentación y síntesis ejecutiva del proyecto.  

---

## 📈 3. Visualizaciones Clave

| Nº | Gráfico | Título | Métrica Clave |
|:--:|:--|:--|:--|
| **1** | Rendimiento Económico | **La Tienda 4 tiene el Menor Ingreso Total** | Ingresos Totales |
| **2** | Reputación del Cliente | **La Tienda 1 muestra la Menor Satisfacción del Cliente (3.98)** | Calificación Promedio (Riesgo Reputacional) |
| **3** | Estructura de la Demanda | **La demanda de Categorías es distinta entre tiendas** | Demanda por Categoría |
| **4** | Inventario y Rotación | **Productos con mayor y menor demanda por tienda** | Productos Top/Flop (Demanda Detallada) |
| **5** | Logística | **La Tienda 1 tiene el Costo de Envío Más Alto** | Costo Promedio de Envío (Ineficiencia Logística) |

Cada visualización busca ofrecer una lectura clara e inmediata del desempeño general y específico de cada tienda, facilitando la toma de decisiones estratégicas.

---

## ⚙️ 4. Ejecución y Dependencias

### 4.1. Ejecución en Google Colab
1. Abre `Desafio_Alura_Store.ipynb` en **Google Colab**.  
2. Carga los archivos CSV (`tienda_1.csv` a `tienda_4.csv`) en el mismo directorio o en tu Google Drive.  
3. Ejecuta todas las celdas en orden: *Entorno de ejecución → Ejecutar todas*.

### 4.2. Instalación Local (opcional)

```bash
pip install pandas folium
````

*(El uso de `folium` es opcional para los mapas; no afecta las conclusiones principales.)*

---

## 📊 5. Conclusión del Análisis

El análisis integral muestra dos escenarios opuestos:

* **Tienda 1:**
  Presenta la calificación promedio más baja (3.98) y el costo logístico más alto, pero también los **mayores ingresos** del grupo.
  Sus problemas son **operativos y gestionables**, vinculados al servicio y la logística.

* **Tienda 4:**
  Registra la **facturación más baja** (≈ 9.8 % inferior a la tienda líder), menor rotación de productos y una estructura de demanda desequilibrada, con alta dependencia en pocas categorías.
  Estas señales reflejan **debilidad estructural y bajo potencial de crecimiento**.

### ✅ **Recomendación Final: Vender la Tienda 4**

**Motivos estratégicos:**

* **Bajo potencial de expansión:** Demanda limitada y productos con bajo movimiento.
* **Estructura poco rentable:** Requiere inversión significativa para alcanzar niveles promedio.
* **Mayor retorno en retener la Tienda 1:** Sus debilidades son internas, no de mercado.

**Conclusión ejecutiva:**
Vender la **Tienda 4** libera capital de un activo con **retorno decreciente**, permitiendo reinvertir en la **optimización de la Tienda 1** y consolidar el crecimiento sostenible de **Alura Store**.

---

## 🤝 6. Autoría

Proyecto desarrollado por **Enrique**
*(con asistencia analítica de IA GEM — obsesionada con la claridad visual y los datos bien contados).*

Si identificas oportunidades de mejora o nuevas perspectivas de análisis, ¡abre un *pull request* o un *issue*! 🚀
