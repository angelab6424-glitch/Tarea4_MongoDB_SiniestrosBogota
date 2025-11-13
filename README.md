# Tarea4_MongoDB_SiniestrosBogota

##  Descripción general
Este repositorio contiene el desarrollo práctico de la **Tarea 4 del curso Big Data**.
El propósito es implementar y analizar una base de datos **NoSQL utilizando MongoDB**, aplicando consultas básicas, filtros y operaciones de agregación sobre un conjunto de datos reales de siniestros viales en la ciudad de Bogotá.

---

## 🗂️ Estructura del repositorio
- **consultas.txt**  
  Contiene todas las consultas utilizadas en MongoDB:
  - Inserción, selección, actualización y eliminación de documentos.  
  - Consultas con filtros y operadores ($gt, $and, etc.).  
  - Consultas de agregación para conteo, promedio y total de registros.  
 

---

## 🧩 Base de datos utilizada
- **Nombre:** `SiniestrosBogotá`  
- **Colección principal:** `siniestros_viales`  
- **Tipo:** Base de datos NoSQL orientada a documentos.  
- **Descripción:**  
  Cada documento representa un accidente reportado en Bogotá e incluye campos relacionados con la fecha, hora, ubicación, condición del actor,   estado, edad, sexo, tipo de vehículo y nivel de gravedad.  
  Esta estructura permite realizar análisis estadísticos y visualizaciones a partir de la información almacenada.

---

## 🧠 Consultas implementadas

### 🔹 Consultas básicas
1. Inserción de documento.  
2. Selección de registros por campo (ejemplo: `SEXO: "MASCULINO"`).  
3. Actualización de campos específicos.  
4. Eliminación de documentos.

### 🔹 Consultas con filtros y operadores
1. Filtro con comparación (`EDAD > 40`).  
2. Filtro con condiciones compuestas (`SEXO = FEMENINO` y `GRAVEDAD = 2`).

### 🔹 Consultas de agregación
1. **Conteo de accidentes por localidad.**  
   Agrupa los registros según el campo `CODIGO_LOCALIDAD` y calcula el total de siniestros.  
2. **Promedio de edad por condición del actor.**  
   Calcula el promedio de edad agrupando por el campo `CONDICION`.  
3. **Total de casos según estado.**  
   Resume la cantidad total de víctimas agrupadas por el campo `ESTADO`.

---

## 🧾 Propósito del análisis
El proyecto busca aplicar los principios del almacenamiento y análisis de datos en entornos **Big Data** utilizando MongoDB como herramienta de apoyo para la manipulación de grandes volúmenes de información.  
Las consultas permiten identificar patrones de accidentalidad, edades más frecuentes y distribución de casos según la condición o el estado de los actores viales.

---

## 👩‍💻 Autoría
Angela Bohorquez. **Big Data**,  
**Escuela de Ciencias Básicas, Tecnología e Ingeniería (ECBTI)** – UNAD.
