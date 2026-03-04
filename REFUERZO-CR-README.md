# Refuerzo por Contact Reason — Nu

Entrenamiento dinámico para refuerzo por Contact Reason (canal Phone). Incluye guía interactiva, casos a practicar, simulaciones de llamada y Ruleta de Conocimiento.

---

## Uso en tu computadora

1. Abre **REFUERZO-CR-actualizado.html** en el navegador (doble clic o arrastra a Chrome/Safari/Edge).
2. O abre **index.html**; te lleva al entrenamiento completo.

Todo el contenido y la lógica están en el HTML y los scripts; los audios (`.wav`) deben estar en la misma carpeta para que suenen en las simulaciones de llamada.

---

## Uso en tu site (pegar código)

Para incrustar el entrenamiento en una plataforma (Weduka, LMS, etc.) donde solo puedes pegar HTML:

1. Abre **REFUERZO-CR-para-site.html** (es la versión con todo el JavaScript ya incluido en un solo archivo).
2. Selecciona todo: **Ctrl+A** (Windows/Linux) o **Cmd+A** (Mac).
3. Copia y pega en el bloque de "código HTML" o "embed" de tu site.
4. Comprueba que el código esté completo: busca al final la línea `<!-- FIN REFUERZO CR -->`. Si aparece, pegaste todo.

**Importante:** Usa **REFUERZO-CR-para-site.html**, no REFUERZO-CR-actualizado.html. El archivo "actualizado" depende de archivos `.js` externos que tu site no tendrá; el "para-site" lleva todo dentro y funciona solo con el pegado.

Si tu plataforma limita la cantidad de caracteres al pegar, puede que se corte. En ese caso tendrías que subir el HTML y los archivos `.js` por separado y enlazarlos (o usar otra opción de hosting).

---

## Archivos del proyecto

| Archivo | Uso |
|--------|-----|
| **REFUERZO-CR-actualizado.html** | Versión principal para abrir en local (usa los .js de la carpeta). |
| **REFUERZO-CR-para-site.html** | Versión todo-en-uno para copiar y pegar en tu site. |
| **refuerzo-cr-logica.js** | Lógica de casos, ruleta, pestañas y simulaciones (ya incluida en "para-site"). |
| **correcciones-refuerzo.js** | Slide 2, botones BPO y "Ir a practicar" (ya incluida en "para-site"). |
| **index.html** | Redirige al entrenamiento completo. |
| **audio-llamada-*.wav** | Audios de las simulaciones de llamada (solo necesarios en local o si los subes a tu site). |

---

## Contenido del entrenamiento

- **Slide 1:** Contact Reasons por BPO (TP / Konecta), enlaces a detalle y mensaje de guía interactiva.
- **Slide 2:** Qué no hacer / qué hacer por Contact Reason, botón "Ir a practicar".
- **Slide 3:** Casos por pestañas (Dudas resultado, Registro/Prospecto, Errores); eliges un caso y pasas a practicar.
- **Slides siguientes:** Caso elegido (contexto, llamada, opciones, feedback, Weduka, siguiente caso).
- **Ruleta:** Girar y responder una pregunta al azar con feedback y enlace a Weduka.

Si necesitas cambiar textos, casos o enlaces, se hace en el HTML (datos en `window.CASOS_MAL_GESTIONADOS`) o en los scripts antes de volver a generar **REFUERZO-CR-para-site.html**.
