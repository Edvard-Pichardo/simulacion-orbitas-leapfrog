# Simulación de Anillos Planetarios con el Integrador Leapfrog

Proyecto de Física Computacional enfocado en la simulación numérica de la
dinámica de anillos planetarios mediante el integrador de Leapfrog,
utilizando Python.

## Descripción

En este proyecto se modela el movimiento de partículas que conforman un anillo
planetario bajo la interacción gravitacional de un planeta central.
El objetivo principal es estudiar la estabilidad orbital, la conservación
de la energía del sistema y el efecto de distintas distribuciones radiales
de densidad.

El trabajo incluye un análisis conceptual sobre la elección del sistema
de referencia, corrigiendo un planteamiento inicial no inercial hacia un
marco de referencia inercial centrado en el planeta.

## Contenido del proyecto
El proyecto se divide en las siguientes secciones:

1. **Introducción**
   - Ecuaciones de movimiento
   - Resonancias y estructura de los anillos

2. **Método de Leapfrog**
   - Fundamento teórico
   - Implementación del integrador
   - Ejemplo de órbita estable unidimensional

3. **Distribución de densidad radial uniforme**
   - Órbita no estable
   - Órbita estable con el planteamiento corregido

4. **Distribución radial con ley de potencia**
   - Análisis teórico
   - Simulaciones para distintos valores del exponente

5. **Anillo con distribución gaussiana**
   - Dependencia con el radio medio y la desviación estándar

6. **Distribuciones radiales mixtas**
   - Combinación de ley de potencia y perfil gaussiano

7. **Resonancias**
   - Análisis teórico
   - Simulación de resonancia 2:1

8. **Conclusiones**

## Metodología
- Lenguaje: **Python**
- Método numérico: **Integrador Leapfrog**
- Visualización: `matplotlib`
- Análisis:
  - Conservación de la energía total
  - Variaciones radiales
  - Histogramas de distribución
  - Evolución temporal de las órbitas

Para cada simulación se muestran:
- Configuración inicial del anillo
- Evolución orbital a tiempos posteriores
- Diferencia porcentual de radios
- Histograma de variaciones radiales
- Conservación de la energía del sistema

## Oportunidades de desarrollo
El código fue desarrollado inicialmente con fines académicos y 
cumple con los objetivos planteados y presenta
resultados consistentes desde el punto de vista físico y numérico.

Como posibles líneas de mejora y desarrollo futuro se identifican:
- Refactorización del código para reducir repetición.
- Encapsulamiento de rutinas en funciones reutilizables.
- Optimización del rendimiento computacional.
- Extensión del modelo a sistemas con mayor número de partículas
  o interacciones adicionales.

Estas oportunidades quedan abiertas para trabajo posterior.

## Autor
**Edvard Pichardo**  
Licenciatura en Física  
Proyecto final — Física Computacional (2025-2)
