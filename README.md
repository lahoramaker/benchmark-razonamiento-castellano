# Benchmark de modelos de razonamiento en castellano

Este repositorio forma parte de una iniciativa de [La Hora Maker](https://youtube.com/@LaHoraMaker) que busca implicar a la comunidad para evaluar las capacidades de razonamiento de diferentes modelos de lenguaje en castellano, con especial énfasis en el modelo Deepseek R1.

## 🎯 Objetivo

Crear un conjunto de preguntas y problemas en castellano que requieran capacidades específicas de razonamiento para su resolución. Este benchmark nos permitirá:

1. Evaluar el rendimiento de modelos especializados en razonamiento como Deepseek R1
2. Comparar sus resultados con modelos base equivalentes
3. Analizar el consumo de tokens y la eficiencia en la resolución
4. Crear un recurso comunitario para entender mejor las capacidades de razonamiento de los LLMs

## 📝 ¿Cómo participar?

Hay dos formas principales de contribuir:

### 1. Crear un Issue

1. Ve a la pestaña "Issues"
2. Haz clic en "New Issue"
3. Utiliza la plantilla proporcionada para describir tu pregunta
4. Incluye tanto el enunciado como la solución esperada

### 2. Enviar un Pull Request

1. Haz fork del repositorio
2. Crea una nueva rama para tu contribución
3. Añade tu pregunta en la carpeta `preguntas/` siguiendo la plantilla
4. Envía el pull request

## 📋 Estructura de las Preguntas

Cada pregunta debe seguir esta estructura:

```markdown
# [ID de la pregunta] - [Título descriptivo]

## Metadata
- Autor: [Tu nombre o usuario]
- Fecha: YYYY-MM-DD
- Categoría: [lógica/matemática/sentido común/otro]
- Dificultad estimada: [fácil/media/difícil]

## Enunciado

[Aquí va tu pregunta o problema. Asegúrate de que esté claramente formulado]

## Solución Esperada

[La respuesta correcta al problema]

## Explicación

[Una explicación detallada de por qué esta es la solución correcta y qué tipo de razonamiento se requiere para llegar a ella]

## Notas Adicionales (opcional)

[Cualquier información adicional relevante, como fuentes, contexto o variaciones del problema]
```

## 🚦 Pautas para Añadir Preguntas

1. **Originalidad**: Las preguntas deben ser originales o, si están basadas en problemas existentes, deben estar adaptadas significativamente.

2. **Claridad**: El enunciado debe ser claro y no ambiguo. Cualquier información necesaria para resolver el problema debe estar incluida.

3. **Razonamiento**: Las preguntas deben requerir razonamiento explícito. No se aceptan preguntas que puedan responderse con simple recuperación de información.

4. **Idioma**: Tanto la pregunta como la solución deben estar en castellano.

5. **Verificabilidad**: La solución debe ser verificable objetivamente. Incluye los pasos de razonamiento necesarios.

6. **Formato**: Sigue estrictamente la plantilla proporcionada.

## 📊 Evaluación

Periódicamente, ejecutaremos las preguntas a través de:
- Deepseek R1 (modelo de razonamiento)
- Un modelo base equivalente (para comparación)

Se registrará:
- Corrección de la respuesta
- Consumo de tokens
- Tiempo de respuesta
- Calidad del razonamiento

Los resultados se publicarán en este repositorio y se discutirán en el canal de La Hora Maker.

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Las contribuciones al repositorio se considerarán bajo la misma licencia.

## 🤝 Contribuidores

- César García (@elsatch)
---

¿Tienes dudas? ¡Únete a la discusión en el canal de La Hora Maker!
