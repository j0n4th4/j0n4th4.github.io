 ---
title: Modelos de procesos de software 
author: Jonathan Stalyn Castro Velez
layout: post
---
**Modelo de Cascada**
<span class="image left"><img src="{{ 'assets/images/cascada.png' | relative_url }}" alt="" /></span>

Las fases están identificadas por separado: 
* El análisis  y definición de requerimientos
* Diseño del sistema y software.
* Pruebas de implementación de unidades
* Integración y pruebas del sistema 
* Operación y mantenimiento 

El principal inconveniente del modelo de la cascada es la dificultad de acomodar el cambio después de que está en marcha el proceso. En principio, una fase tiene que ser completada antes de pasar a la siguiente fase.

**Desarrollo incremental**

<span class="image left"><img src="{{ 'assets/images/incremental.png' | relative_url }}" alt="" /></span>

***Beneficios:*** 
* El costo de atender las necesidades cambiantes de los clientes se reduce. 
  * La cantidad de análisis y la documentación que tiene que ser hecho de nuevo es mucho menor que la que se requiere con el modelo de cascada. 
* Es más fácil obtener retroalimentación de los clientes en el trabajo de desarrollo que se ha hecho.
  * Los clientes pueden hacer comentarios sobre las manifestaciones del software y ver cuánto se ha implementado. 
* Más rápida entrega y despliegue de software de utilidad para el cliente es posible. 
  * Los clientes pueden usar y obtener valor a partir del software anterior que es posible con un proceso de cascada.

***Problemas:*** 
* El proceso no es visible.
  * Los gerentes necesitan entregas regulares para medir el progreso. Si se desarrollan rápidamente los sistemas, no es rentable para producir documentos que reflejen todas las versiones del sistema.
* Estructura del sistema tiende a degradarse a medida que se añaden nuevos incrementos. 
  * A menos tiempo y dinero que se gasta en la refactorización para mejorar el software, cambio regular tiende a corromper su estructura. La incorporación de nuevos cambios de software se vuelve cada vez más difícil y costoso. 

**Espiral**

<span class="image left"><img src="{{ 'assets/images/espiral.png' | relative_url }}" alt="" /></span>

**Definición:** 
Es un modelo de ciclo de vida desarrollado por Barry Boehm en 1988. 

Las actividades de este modelo son una espiral, cada bucle es una actividad. 

Las actividades no están fijadas a prioridad, sino que las siguientes se eligen en función del análisis de riesgo, comenzando por el bucle interior.

En este modelo, el esfuerzo de desarrollo es iterativo. Tan pronto como uno completa un esfuerzo de desarrollo, otro comienza. Además, en cada desarrollo ejecutado, puedes seguir estos cuatros pasos.
1. Determinar qué quieres lograr. 
2. Determinar las rutas alternativas que puedes tomar para lograr estas metas. Por cada una, analizar los riesgos y resultados finales, y seleccionar la mejor. 
3. Seguir la alternativa seleccionada en el paso 2. 	
4. Establecer qué tienes terminado. 

**Desarrollo Rápido de Aplicaciones (DRA)**


<span class="image left"><img src="{{ 'assets/images/aplicaciones.png' | relative_url }}" alt="" /></span>







