# Prompt Engineer

Guía práctica para redactar mejores prompts y obtener respuestas más útiles, precisas y consistentes de modelos de lenguaje como ChatGPT.

---

## Enfoque general

- **Prioriza la claridad del mensaje**, no la estructura del texto.  
  Lo importante es que la IA entienda tu intención de forma directa, no que el prompt se vea bonito.
  
- **Evita saludos o agradecimientos innecesarios.**  
  Mensajes como “hola”, “gracias” o “por favor” no aportan al contexto y pueden distraer del objetivo principal.

- **Da contexto siempre.**  
  Si no proporcionas información suficiente, el modelo la **inventará o asumirá** según su entrenamiento.  
  Cada dato que omites, la IA lo elige por ti.
  
- **Dile que haga preguntas en caso de tenerlas.**
  Dile ¨Hazme preguntas antes de responderme¨
---

## Principios clave

1. **Sé explícito.**  
   Cuanto más claro seas, menos margen de interpretación tendrá la IA.  
   Ejemplo:  
   “Haz un resumen.”  
   “Haz un resumen de 100 palabras que enfatice los conceptos técnicos.”

2. **Corrige a la IA.**  
   Si no sigue tus instrucciones o se desvía, **indícaselo directamente**.  
   Ejemplo: “No hiciste lo que pedí, vuelve a hacerlo pero sin incluir ejemplos.”

3. **Evita detalles irrelevantes.**  
   Cada palabra debería aportar información útil. Elimina lo decorativo o redundante.

4. **Controla el tono y el formato.**  
   Si quieres un resultado en cierto estilo (profesional, informal, técnico, narrativo, etc.), **especifícalo**.  
   Ejemplo: “Explica esto como si fuera un artículo académico con citas.”

5. **Divide tareas complejas.**  
   Si el objetivo es grande, pídele que trabaje por etapas:  
   - Paso 1: Analiza el problema.  
   - Paso 2: Propón soluciones.  
   - Paso 3: Genera el texto final.

---

## 🧩 Buenas prácticas

- **Usa roles o contextos.**  
  Ejemplo: “Actúa como un profesor de matemáticas que explica conceptos con ejemplos simples.”

- **Indica el formato de salida.**  
  Ejemplo: “Devuelve la respuesta en formato JSON / tabla / Markdown.”

- **Controla el nivel de detalle.**  
  Usa indicaciones como “explicación breve”, “nivel experto” o “resumen ejecutivo”.

- **Valida y ajusta.**  
  Después de obtener la respuesta, evalúa si cumplió tu objetivo y **ajusta el prompt** en función de eso.

---

## Estructura sugerida (opcional)

Aunque la claridad es lo más importante, una estructura básica puede ayudarte:

```text
[Rol o contexto]  
[Instrucción principal]  
[Detalles clave o restricciones]  
[Formato de salida esperado]
