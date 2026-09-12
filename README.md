# 🍷 Análisis de Correspondencias: Consumo de Alcohol en Estudiantes

<!-- Animación de Datos/Estadística -->
<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcG1wYzFzZW1wZ3ExZnc0bzF5eG9wYWw0b2c3dXZyd3R6bTczcWFmMCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/3o7TksjJsG5421X6xO/giphy.gif" width="150" alt="Data Analytics Animation" />
</div>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
  <img src="https://img.shields.io/badge/Estadística_Multivariada-7B1FA2?style=for-the-badge" alt="Stats" />
  <img src="https://img.shields.io/badge/Análisis_de_Datos-00838F?style=for-the-badge" alt="Data" />
</p>

> **Objetivo del Proyecto:** Analizar los hábitos de consumo de alcohol en estudiantes de secundaria (áreas de Matemáticas y Portugués) y su relación con el entorno social y familiar mediante técnicas estadísticas multivariadas.

---

### 📊 Contexto y Metodología

El estudio se basó en el procesamiento de una base de datos de **382 casos** a partir de una encuesta de **33 ítems**, evaluando aspectos como tiempo libre, convivencia, relaciones interpersonales y rendimiento escolar.

*   **Lenguaje y Modelado:** R (para pruebas de hipótesis y modelado multivariado).
*   **Pruebas Estadísticas:** Pruebas de Independencia Ji-cuadrada ($\chi^2$) para evaluar significancia ($p < 0.05$).
*   **Modelo Multivariado:** Análisis de Correspondencias Múltiples (ACM) para la reducción de dimensionalidad y visualización de perfiles.

---

### 📈 Hallazgos Principales

*   🔍 **Factores Significativos:** Aunque se evaluaron múltiples variables (zona de vivienda, actividades extracurriculares, acceso a internet, tamaño de familia), las pruebas $\chi^2$ demostraron que únicamente el **Sexo** y la **Frecuencia de salida con amigos** guardan una dependencia estadísticamente significativa con el consumo de alcohol en fines de semana.
*   📉 **Varianza Explicada:** El modelo de Análisis de Correspondencias logró capturar y explicar el **67.02%** de la variabilidad total de los datos utilizando únicamente dos dimensiones.
*   👤 **Perfiles Identificados:**
    *   *Bajo Consumo:* Asociado principalmente a mujeres con baja frecuencia de salidas con amigos.
    *   *Alto Consumo:* Presente con mayor frecuencia en hombres y estudiantes con alta interacción social.

---

### 📚 Recursos y Documentación

Puedes explorar los materiales visuales y el reporte completo de la investigación:

<div align="center">
  <a href="https://github.com/vanemendez25/analisis-correspondencias-alcohol-estudiantes/blob/main/Cartel.multivariados.pdf">
    <img src="https://img.shields.io/badge/📊_Ver_Póster_del_Proyecto-PDF-blue?style=for-the-badge" alt="Ver Póster" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/vanemendez25/analisis-correspondencias-alcohol-estudiantes/blob/main/Proyecto.Analisis.de.Correspondencia.pdf">
    <img src="https://img.shields.io/badge/📄_Ver_Reporte_Estadístico-PDF-red?style=for-the-badge" alt="Ver Reporte" />
  </a>
</div>

---

### 👩🏻‍💻 Equipo de Investigación
Proyecto desarrollado colaborativamente para la Licenciatura en Ingeniería en Ciencia de Datos en la **Universidad Veracruzana**:

*   **Vanessa Méndez Lara** - [@vanemendez25](https://github.com/vanemendez25)
*   **Karla Valeria Fernández Mendoza**- [@Karla800](https://github.com/karla800)
*   **Dra. Judith Gpe. Montero Mora**
