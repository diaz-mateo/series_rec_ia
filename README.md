CODERHOUSE
DIPLOMATURA
Desarrollador Web Full Stack

CURSO:
IA: Generación de Prompts
Carreras Intensivas
COMISIÓN: 76190

PRESENTACIÓN
Preentrega #1
Sistema de Recomendación de Series con IA

PROFESOR:
Ezequiel Matías Tartaglia

ALUMNO:
Mateo Díaz Paredes

MÓDULO II

1. Introducción y Contexto
En la actualidad, el consumo de series y contenido audiovisual ha experimentado un crecimiento exponencial gracias a la expansión de las plataformas de streaming y la diversidad de producciones disponibles. Sin embargo, los usuarios se enfrentan a la dificultad de encontrar nuevas series que se ajusten a sus gustos personales. Las recomendaciones genéricas o basadas en rankings y opiniones de terceros muchas veces no logran captar las particularidades de las preferencias individuales.

El presente proyecto propone el desarrollo de un sistema de inteligencia artificial que ofrezca recomendaciones de series personalizadas. Utilizando modelos avanzados de lenguaje como los proporcionados por Google Gemini, el sistema analiza la serie favorita del usuario y genera una lista de propuestas que comparten características en términos de género, temática, estilo narrativo y audiencia.

2. Presentación del Problema
Problema a abordar:

Los usuarios disfrutan de ver series, pero a menudo se sienten abrumados por la enorme cantidad de contenido disponible.
Las recomendaciones convencionales basadas en listas predefinidas o en la opinión general del público no siempre se adaptan a los gustos personales.
La búsqueda manual de nuevas series requiere de tiempo y esfuerzo, lo que reduce la experiencia de entretenimiento.
Relevancia del problema:

Un sistema inteligente que ofrezca sugerencias personalizadas puede transformar la manera en que los usuarios descubren contenido, ahorrándoles tiempo y aumentando la satisfacción.
Este tipo de herramienta se vuelve especialmente valiosa en entornos donde el catálogo es muy amplio y heterogéneo, como en las principales plataformas de streaming.
Al implementar una solución basada en IA, se permite un análisis profundo y dinámico de las preferencias individuales, generando recomendaciones que van más allá de simples estadísticas.
3. Propuesta de Solución
Objetivo general:
Desarrollar un sistema de IA que, a partir de la entrada del usuario (nombre de una serie favorita), genere una lista de recomendaciones de series similares, acompañado de explicaciones detalladas de por qué dichas series son adecuadas según ciertos criterios (género, temática, estilo narrativo, audiencia).

Metodología y enfoque técnico:

Análisis de entrada:
La aplicación solicita al usuario que ingrese el nombre de una serie que le haya gustado.
Se realiza una validación básica de la entrada para asegurar que no esté vacía.
Procesamiento y consulta:
Utilizando la API de Google Gemini, el sistema envía un prompt diseñado para generar recomendaciones de series similares, justificando la selección.
Paralelamente, se extraen únicamente los nombres de las series recomendadas a través de otro prompt especializado.
Generación de contenido visual y análisis extendido:
Se emplea un modelo de visión (actualizado a "gemini-1.5-flash") para generar una descripción de imagen que represente de forma visual las series sugeridas.
Se incorpora un análisis extendido que profundiza en los motivos de las recomendaciones, considerando similitudes en género, narrativa y público objetivo.
Almacenamiento y gestión de resultados:
Los resultados se guardan en un archivo JSON, permitiendo la creación de una caché que agilice consultas futuras.
Se mantiene un reporte de la sesión para llevar un registro de todas las series procesadas durante la ejecución.
Características adicionales:

Interactividad: El sistema permite múltiples iteraciones, ofreciendo un menú interactivo (basado en consola) donde el usuario puede ingresar nuevas series, consultar resultados previos o ver un resumen de la sesión actual.
Reporte de sesión: Se genera un informe que resume todas las recomendaciones y análisis realizados en la sesión, facilitando la revisión y comparación de resultados.
Actualización de datos: En caso de que ya existan recomendaciones almacenadas para una serie en particular, el usuario tiene la opción de actualizar la información o utilizar los datos en caché.
4. Plan de Implementación y Cronograma
Fases del desarrollo:

Diseño y planificación (Semana 1-2):
Definición de la arquitectura del sistema y del flujo de datos.
Selección y configuración de las APIs y modelos de IA (Google Gemini).
Elaboración del diseño de la base de datos y el sistema de caché.
Implementación inicial (Semana 3-5):
Desarrollo del módulo de entrada y validación de datos.
Integración de la API de Google Gemini para generar recomendaciones y análisis extendido.
Creación de funciones para extraer nombres de series y generar descripciones de imagen.
Optimización y pruebas (Semana 6-7):
Realización de pruebas unitarias y de integración.
Optimización del rendimiento y manejo de errores.
Incorporación de funcionalidades adicionales, como el reporte de sesión y el menú interactivo.
Presentación y documentación final (Semana 8):
Preparación de la presentación del proyecto.
Redacción de la documentación técnica y del manual de usuario.
Ajustes finales y despliegue en entorno de pruebas.
Recursos necesarios:

Hardware: Computadora con capacidad suficiente para ejecutar Python y conectividad a internet para consumir APIs.
Software: Entorno de desarrollo (Jupyter Notebook, Visual Studio Code, etc.), instalación de bibliotecas necesarias (google-generativeai, ipywidgets, etc.).
Conocimiento: Dominio en programación con Python, manejo de APIs, conceptos de inteligencia artificial y generación de prompts.
5. Impacto y Beneficios Esperados
Beneficios para el usuario final:

Personalización: Recomendaciones basadas en gustos específicos, lo que aumenta la relevancia y satisfacción al descubrir nuevas series.
Eficiencia: Reducción del tiempo invertido en buscar contenido, gracias a un sistema automatizado y basado en análisis avanzado.
Experiencia enriquecida: La integración de descripciones visuales y análisis extendido añade un valor añadido, facilitando la comprensión del porqué de cada recomendación.
Beneficios para el mercado y las plataformas de streaming:

Diferenciación: Ofrecer una herramienta de recomendación personalizada puede diferenciar una plataforma de la competencia.
Retención de usuarios: Al mejorar la experiencia de descubrimiento, se fomenta una mayor retención y fidelización del usuario.
Optimización de contenido: Permite un mejor aprovechamiento del extenso catálogo disponible, ayudando a destacar producciones que podrían pasar desapercibidas.
6. Conclusiones y Perspectivas Futuras
Este proyecto de “Sistema de Recomendación de Series con IA” representa una solución integral y avanzada para abordar uno de los desafíos actuales en el consumo de contenido audiovisual. La aplicación de modelos de lenguaje y visión de última generación permite no solo generar recomendaciones personalizadas, sino también ofrecer una explicación detallada que respalde la selección de series.

Conclusiones:

La solución propuesta es técnica y prácticamente viable, dado el acceso a herramientas de IA avanzadas y la existencia de APIs robustas como Google Gemini.
El sistema mejora significativamente la experiencia del usuario, al ofrecer sugerencias basadas en un análisis profundo de sus preferencias.
El enfoque modular y escalable del proyecto permite futuras mejoras, como la integración con bases de datos más amplias o la incorporación de algoritmos de aprendizaje automático para refinar aún más las recomendaciones.
Perspectivas futuras:

Integración con plataformas de streaming: Adaptar el sistema para que pueda integrarse directamente en plataformas de contenido, ofreciendo recomendaciones en tiempo real.
Mejoras en el análisis de datos: Incorporar técnicas de machine learning para aprender de las interacciones del usuario y optimizar las recomendaciones con el tiempo.
Expansión a otros tipos de contenido: Ampliar el enfoque del sistema para recomendar no solo series, sino películas, documentales u otros formatos audiovisuales.
Este documento, junto con la implementación del código (actualizado al modelo "gemini-1.5-flash" para la generación de descripciones visuales), respalda la viabilidad técnica y comercial del proyecto. Se espera que, con la implementación de este sistema, se mejore la experiencia del espectador al descubrir nuevas series, haciendo el proceso de búsqueda más intuitivo, rápido y personalizado.
