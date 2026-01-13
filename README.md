# telecom-analysis

# 📊 Proyecto 6 – Análisis de una empresa de telecomunicaciones

## 🧠 Contexto del negocio

ConnectaTel es una empresa de telecomunicaciones con operaciones en **México y Colombia**. El objetivo de este proyecto es **comprender cómo los clientes utilizan realmente los servicios móviles**, específicamente llamadas y mensajes, para identificar patrones de uso, detectar comportamientos atípicos y definir segmentos de clientes con necesidades diferenciadas.

El análisis busca apoyar la **optimización de la oferta comercial**, la **mejora de la experiencia del usuario** y la **toma de decisiones basada en datos**.


## 🎯 Objetivo del proyecto

Construir una visión **clara, confiable y accionable** del comportamiento de uso de los clientes a partir de la integración, limpieza y análisis de múltiples fuentes de datos, identificando:

* Patrones de uso de llamadas y mensajes
* Segmentos de clientes por edad y nivel de uso
* Comportamientos atípicos (outliers)
* Oportunidades comerciales y de mejora


## 💡 Preguntas de negocio

* ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
* ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
* ¿Cómo varía el uso según la edad y el tipo de plan contratado?
* ¿Qué patrones pueden ayudar a diseñar mejores planes y mejorar la satisfacción del cliente?


## 🗂️ Fuentes de datos

El análisis se basa en tres datasets principales:

* **plans.csv**
  Catálogo de planes disponibles, incluyendo precios, minutos incluidos, GB incluidos y costos por consumo extra.

* **users_latam.csv**
  Información de los clientes: edad, ciudad, país, fecha de registro, plan contratado y estado de churn.

* **usage.csv**
  Detalle del uso real del servicio: llamadas, mensajes, duración y longitud.

Estos datasets se complementan para analizar el comportamiento de los usuarios y su relación con el plan contratado.


## 🛠️ Herramientas utilizadas

* Python
* pandas
* numpy
* seaborn
* matplotlib
* Jupyter Notebook

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar este repositorio
2. Instalar dependencias:

   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
3. Abrir el notebook principal:

   ```bash
   jupyter notebook
   ```
4. Ejecutar las celdas en orden para reproducir el análisis

---

## 📌 Entregables

* Jupyter Notebook con el análisis completo
* Visualizaciones y segmentaciones documentadas
* Este README para reproducción y entendimiento del proyecto

---

## 👤 Autor

**Luis Adrian Juarez**
QA Lead / Data Analyst
Proyecto académico – Análisis de datos en telecomunicaciones
