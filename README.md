# 📊 ConnectaTel - Customer Segmentation & Usage Analysis

## 📌 Objetivo del Proyecto
El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel utilizando técnicas de limpieza, transformación y análisis exploratorio de datos.

A través del análisis, se busca:

- Detectar problemas de calidad de datos.
- Identificar patrones de uso de clientes.
- Segmentar usuarios según edad y nivel de consumo.
- Detectar posibles outliers.
- Generar insights accionables para el negocio.

---

# 🗂️ Datasets Utilizados
El proyecto utiliza los siguientes datasets:

- `users.csv`
  - Información de usuarios.
  - Variables como edad, ciudad, fecha de registro y plan.

- `usage.csv`
  - Registro de uso de llamadas, mensajes y duración.

---

# 🧹 Etapas del Análisis
## 1. Exploración Inicial de Datos
- Revisión de estructura general.
- Identificación de tipos de datos.
- Detección de valores nulos y sentinels.

## 2. Limpieza de Datos
- Corrección de sentinels (`-999`, `"?"`).
- Conversión de fechas.
- Eliminación/corrección de fechas inválidas.
- Tratamiento de missing values.
- Revisión de inconsistencias.

## 3. Análisis de Missingness
- Diagnóstico de datos MAR (Missing At Random).
- Justificación del tratamiento de valores nulos.

## 4. Detección de Outliers
- Uso de método IQR.
- Evaluación de valores extremos.
- Decisión de mantener outliers relevantes para negocio.

## 5. Creación de Variables
- Cantidad de mensajes.
- Cantidad de llamadas.
- Minutos totales de llamadas.

## 6. Segmentación de Clientes

### Segmentación por Uso
- Bajo uso
- Uso medio
- Alto uso

### Segmentación por Edad
- Joven
- Adulto
- Adulto Mayor

## 7. Visualización de Datos
- Countplots de segmentos.
- Distribución de usuarios.
- Interpretación visual de patrones.

## 8. Insight Ejecutivo
- Conclusiones de negocio.
- Recomendaciones estratégicas.
- Oportunidades de mejora de planes.

---

# ▶️ Cómo Ejecutar el Proyecto

## Requisitos
Instalar las siguientes librerías:

```bash
pip install pandas numpy matplotlib seaborn
```

## Ejecutar el Notebook
1. Clonar este repositorio:

```bash
git clone LINK_DE_TU_REPOSITORIO
```

2. Entrar a la carpeta del proyecto:

```bash
cd nombre-del-repo
```

3. Abrir Jupyter Notebook:

```bash
jupyter notebook
```

4. Abrir el archivo `.ipynb`.

5. Ejecutar las celdas en orden.

---

# 🔁 Guía de Reproducción
1. Descargar o clonar el repositorio desde GitHub.
2. Instalar las dependencias necesarias.
3. Abrir el notebook del proyecto.
4. Ejecutar todas las celdas secuencialmente.
5. Revisar visualizaciones, segmentaciones e insights generados.

---

# 📈 Principales Hallazgos
- Se detectaron problemas de calidad de datos como sentinels y fechas inválidas.
- La mayoría de los usuarios pertenece al segmento adulto.
- Los usuarios de uso medio y alto representan la mayor parte de la base activa.
- Se encontraron outliers relevantes que podrían representar clientes premium.
- Existen oportunidades para crear planes segmentados según comportamiento de consumo.

---

# 👩‍💻 Autor
Amy Sulbaran
Proyecto desarrollado como parte del Sprint 7 - Data Analytics.
