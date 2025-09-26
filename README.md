<div align="center">
  
# QA-Postman-4to-sprint

</div>
  
#  QA – Pruebas de API en Urban.Grocers 🛒

Este repositorio contiene las **pruebas de API realizadas con Postman** sobre el proyecto **Urban.Grocers**, como parte del Bootcamp de QA Engineering en TripleTen.

## 📌 Objetivo
Validar los endpoints de **kits** y **servicios de entrega**, comprobando tanto escenarios positivos como negativos.

## ⚙️ Endpoints probados
1. **Kits** – Agregar comestibles a un kit  
   - `POST /api/v1/kits/{id}/products`  
   - Restricción: la lista de productos no puede superar los **30 elementos**.  
   - Se verificaron respuestas **200 OK** y **400 Bad Request** según los casos.

2. **Servicios de entrega** – Order and Go  
   - `POST /order-and-go/v1/delivery`  
   - Validación de disponibilidad y cálculo del precio de entrega.  
   - Se verificaron respuestas en diferentes escenarios de entrada.

## 🧪 Pruebas realizadas
- ✅ Pruebas positivas: agregar productos válidos, calcular costo de entrega en condiciones válidas.  
- ❌ Pruebas negativas: exceder límite de productos, datos inválidos en la solicitud, direcciones incorrectas, etc.  

## 📂 Contenido
- [`UrbanGrocers_API.postman_collection.json`](https://github.com/lucyfannia/QA-Postman-4to-sprint/blob/main/Lucy%20Arzate%20%2C%20grupo%2040%2C%204er%20sprint.postman_collection.json) → Colección de pruebas Postman.  
- [`UrbanGrocers_Env.postman_environment.json`](environments/UrbanGrocers_Env.postman_environment.json) → Variables de entorno (si aplica).  
- [`Requisitos_UrbanGrocers.pdf`](https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-sprint-3/QA_3.1.1_Requisitos_para_el_back-end_de_Urban.grocers.pdf) → Requisitos del back-end.  
- [`Checklist_Pruebas.xlsx`](https://docs.google.com/spreadsheets/d/1kbGYznBHBtw74YLfojU-QdkZs5f2wIHI4GFnpTc9dnk/edit?gid=802585125#gid=802585125) → Lista de comprobación de casos de prueba.
 

## 🚀 Ejecución
1. Importar la colección en Postman (`File > Import`).  
2. Seleccionar el environment correspondiente.  
3. Ejecutar las pruebas desde el **Runner**.  

## 📊 Logros
- **+20 casos de prueba ejecutados** (positivos y negativos).  
- Identificación de **múltiples escenarios de error 400** documentados en la checklist.  
- Validación completa de restricciones de negocio (límite de 30 productos, precios de entrega).  

---


<div align="center">
