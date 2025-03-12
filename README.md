# Urban Routes - Diseño de Pruebas

## Descripción del Proyecto
Este proyecto forma parte del segundo sprint del programa de formación en QA Engineer de TripleTen. El objetivo principal fue analizar, diseñar y documentar pruebas para la funcionalidad de compartir un automóvil dentro de la aplicación Urban Routes.

Urban Routes es una aplicación que permite a los usuarios crear rutas de viaje y calcular la duración y el precio del trayecto según distintos tipos de transporte, incluyendo automóvil propio, a pie, taxi, bicicleta, scooter y compartir un automóvil. En este ejercicio, el enfoque estuvo en la función de compartir un automóvil.

## Objetivo
El objetivo principal es garantizar la calidad de la funcionalidad de compartir un automóvil mediante técnicas de diseño de pruebas como clases de equivalencia, valores límite y diagramas de flujo.

## Actividades Realizadas

### 1. Mapa Mental para "Agregar Licencia de Conducir"
Se elaboró un mapa mental utilizando draw.io para visualizar la estructura de la funcionalidad. El mapa incluye dos secciones:
- Interfaz: Definición de los elementos de la UI y su disposición.
- Funcionalidad: Validaciones para la entrada de datos (formatos correctos e incorrectos), comportamientos esperados y escenarios límite.

➡️ Si deseas ver el mapa mental da clic [aquí](https://drive.google.com/file/d/13bksXhiwlHhyrrayxLePrjJPcSk1V6qN/view?usp=sharing).

### 2. Clases de Equivalencia y Valores Límite para Campos de Entrada
Se definieron clases de equivalencia y valores límite para los campos "Nombre" y "Apellido" en el formulario de licencia de conducir. Se identificaron:

- Clases de entrada válidas e inválidas.
- Valores límite para detectar posibles errores en validaciones.
- Casos de prueba que verifican diferentes combinaciones de entradas válidas e inválidas.

➡️ Si deseas ver las clases de equivalencia da clic [aquí](https://docs.google.com/spreadsheets/d/1GvsiYwBrkYeEOPNh1G-58cpbA9AEP2pA/edit?gid=1899960451#gid=1899960451).

### 3. Diagrama de Flujo para Cálculo de Precio y Duración del Viaje
Se creó un diagrama de flujo para visualizar el algoritmo que determina la duración del viaje según la velocidad y la distancia. Se consideraron los siguientes elementos:

- Dependencia de la velocidad según la hora de salida.
- Aplicación de la fórmula: T = S / V (duración del viaje) y Precio = T * precio por minuto.
- Manejo de casos especiales, como viajes con distancia cero.

➡️ Si deseas ver el diagrama de flujo da clic [aquí](https://drive.google.com/file/d/1Z6dXkoiy72Xj-RwyoCwzlHVF3f3N_utH/view?usp=sharing).

### 4. Diseño de Casos de Prueba para Validar Cálculo de Precio y Duración
Basado en el análisis de clases de equivalencia, se diseñaron casos de prueba para verificar:

- Cálculo correcto de la duración del viaje considerando diferentes velocidades y distancias.
- Cálculo del precio del viaje con base en la duración y la tarifa.
- Escenarios extremos, como una distancia de 0 km.

➡️ Si deseas ver los casos de prueba da clic [aquí](https://docs.google.com/spreadsheets/d/1GvsiYwBrkYeEOPNh1G-58cpbA9AEP2pA/edit?gid=1633448385#gid=1633448385).

## Conclusión
Este proyecto permitió aplicar metodologías de análisis de requisitos, diseño de pruebas y documentación de QA. La experiencia adquirida refuerza la importancia de la validación de entrada de datos, la lógica de negocio y la precisión en cálculos críticos dentro de una aplicación de movilidad.


---
📌 **Autor:** Jorge Luis Pasten Peña
📅 **Sprint:** 2
🚀 **Estado:** Finalizado
