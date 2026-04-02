# mi-corazon-ar
# ❤️ Realidad Aumentada Aplicada: Visualización y Control del Ritmo Cardíaco

Este proyecto presenta una solución de **Realidad Aumentada basada en Web (WebAR)** para la interacción con modelos anatómicos en tiempo real. Mediante el uso de marcadores de visión artificial personalizados, se permite la visualización dinámica y la manipulación de la fisiología cardíaca simulada.
Para la utilización de la simulación sería necesario imprimir los 3 marcadores, el marcador 1 al ser enfocado provoca la aparicion de un video de realidad aumentada con un corazón centrado en la imagen del marcador que late a una frecuencia normal, si se introduce el marcador 2 o el 3 en la imagen captada por la cámara provoca un efecto de taquicardia o bradicardia respectivamente.

## ✍️ Autoría y Registro (Referencia Principal)

Para citar el uso de esta herramienta, el código o la metodología empleada, utilice la siguiente referencia:

* **Referencia sugerida:** Gabucio López, A. (2026). *Experiencia Interactiva de Realidad Aumentada: Corazón Humano*. Repositorio de software de acceso abierto. DOI: [PENDIENTE DE ASIGNACIÓN EN ZENODO].
* **Autor:** Antonio Gabucio López
* **ORCID:** [0000-0001-6000-9937](https://orcid.org/0000-0001-6000-9937)
* **DOI:** [INSERTAR AQUÍ EL DOI UNA VEZ GENERADO]

## 📊 Resumen del Proyecto

Esta herramienta ha sido diseñada como un recurso de innovación docente y divulgación. Utiliza el stack tecnológico **AR.js** y **A-Frame** para implementar una arquitectura de eventos que modifica el parámetro `timeScale` de las animaciones en respuesta a la detección de patrones específicos (`.patt`).

### Interacción Multimarcador:
* **Marcador 1 (Ancla):** Renderizado del modelo anatómico en estado basal.
* **Marcador 2 (Acelerador):** Simulación de taquicardia (frecuencia x4).La apariencia del marcador es SNS, acrónimo de Sistema nervioso simpático
* **Marcador 3 (Ralentizador):** Simulación de bradicardia (frecuencia x0.3).La apariencia del marcador es SNP, acrónimo de Sistema nervioso parasimpático

## 🛠️ Metodología y Colaboraciones

En la elaboración de esta herramienta técnica se han utilizado los siguientes recursos y asistencias:

1. **Desarrollo y Documentación:** Programación de la lógica de interacción y optimización del flujo WebAR por Antonio Gabucio López, con la colaboración de **Gemini (Modelo de IA de Google)** en la arquitectura del código y la redacción técnica.
2. **Generación de Marcadores:** Los archivos de patrón se han obtenido mediante la herramienta disponible en: [https://antoniogabucio.github.io/AR-marker-generator/].
3. **Recurso Gráfico Integrado:** Se ha incorporado el modelo 3D ["Animated Beating Heart"](https://skfb.ly/6XPZL) de **nitwit.friends** (Licencia CC BY 4.0) como componente visual de la herramienta.

## 🚀 Acceso a la Aplicación (Demo Live)

La experiencia es funcional desde cualquier navegador móvil moderno en:
`https://antoniogabucio.github.io/mi-corazon-ar/`

---
*Este repositorio se distribuye bajo la licencia MIT.*


--
*Este repositorio se distribuye bajo la licencia MIT. Las sugerencias para la mejora del rendimiento en dispositivos móviles son bienvenidas.*
