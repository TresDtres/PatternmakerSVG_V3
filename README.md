# Advanced SVG Path Editor v3.0

## ✨ Agradecimientos

Este proyecto fue desarrollado por TresDtres.

La validación de la idea, el refinamiento conceptual y la estructuración de la documentación para la versión 3.0 contaron con la colaboración y asistencia de **Gemini**, un modelo de lenguaje de Google AI. Su participación fue clave para enfocar las características de la herramienta hacia el nicho de la creación de datos para Machine Learning.



This is a web-based, interactive Bézier curve editor built with React and TypeScript. It allows users to create and manipulate complex SVG paths with precision and ease. Version 3.0 transforms this tool from a simple drawing application into a powerful data-creation platform for AI and machine learning, specifically tailored for pattern making.

## What's New in Version 3.0

This is a landmark update focused on adding **data, precision, and workflow acceleration**, turning the editor into a professional tool for creating AI training datasets for pattern design.

-   **Properties Panel & Data Export for AI:**
    -   A new **Properties Panel** allows you to add rich, semantic metadata to your designs.
    -   **Global Labels:** Define a `Piece Name` and `Size` for the entire pattern.
    -   **Node Labels:** Assign alphanumeric labels (e.g., 'A', '1') and descriptions to key points. Labels are displayed directly on the canvas.
    -   **Segment Labels:** Add descriptions to path segments (e.g., "Side Seam", "Armhole").
    -   **Intelligent SVG Export:** All this metadata is embedded as a clean JSON object within the exported SVG, creating "smart" patterns ready for AI training pipelines.

-   **Precision Measurement Tools:**
    -   **Toggle Measurements:** A new toolbar button allows you to show or hide the precise length (in cm) of every segment on your path.
    -   **Live Feedback:** As you draw a new line or drag a point, a live measurement appears next to your cursor, showing the exact length or distance.

-   **Shape Primitives:**
    -   Instantly generate common base shapes.
    -   Create **Squares, Rhombuses, and Circles** with custom dimensions through a simple dialog.

## Features

-   **Dual Editing Modes:** Switch between **Pattern Mode** (for straight-line structural work) and **Bézier Mode** (for curve refinement).
-   **Data Labeling Panel:** Assign properties like Piece Name, Size, and custom labels/descriptions to nodes and segments.
-   **Intelligent SVG Export:** Exports paths with all metadata embedded as a structured JSON object, ready for AI/ML pipelines.
-   **Measurement Tools:** Toggle on-canvas display of segment lengths and see live measurements while editing.
-   **Shape Primitives:** Instantly create squares, rhombuses, or circles with specified dimensions.
-   **Apply Symmetry:** Create perfectly symmetrical shapes by reflecting a closed path across a selected straight edge.
-   **Path Manipulation:** Full control over nodes, curves, and segments.
-   **Undo/Redo:** A robust history system that tracks all changes, including label edits.
-   **Snap to Grid, Pan & Zoom:** Standard professional canvas navigation and control.
-   **Export to SVG:** Export your creation as a clean, data-rich `.svg` file.

## How to Use

1.  **Start a Project:** Use the **Shape Primitives** (Square, etc.) to start with a base, or begin drawing in **Pattern Mode**.
2.  **Structure & Refine:** Use **Pattern Mode** for the basic outline with straight lines. Switch to **Bézier Mode** to perfect the curves.
3.  **Label Your Data:**
    -   Open the **Properties Panel**.
    -   With nothing selected, enter the global **Piece Name** and **Size**.
    -   Click on a node (anchor point) to give it a **Label** and **Description**.
    -   Click on a line segment to add a **Segment Description**.
4.  **Check Dimensions:**
    -   Click the **"Show/Hide Measurements"** button to verify the lengths of all segments.
    -   Watch the live measurement feedback as you drag points to make precise adjustments.
5.  **Apply Symmetry:** For symmetrical pieces, close the path, click **"Apply Symmetry"**, and select a straight edge to mirror the object.
6.  **Navigate:** Use the **mouse wheel** to zoom and **spacebar + drag** to pan. **Right-click** to deselect any active element.
7.  **Export:** Click **"Export to SVG"** to save your pattern. The resulting file will contain both the visual path and all the metadata you entered, ready for your AI project.

---

# Editor de Trazados SVG Avanzado v3.0

Este es un editor de curvas Bézier interactivo basado en la web, construido con React y TypeScript. Permite a los usuarios crear y manipular trazados SVG complejos con precisión y facilidad. La versión 3.0 transforma esta herramienta de una simple aplicación de dibujo a una potente plataforma de creación de datos para IA y machine learning, especialmente diseñada para patronaje.

## Novedades en la Versión 3.0

Esta es una actualización histórica centrada en añadir **datos, precisión y aceleración del flujo de trabajo**, convirtiendo el editor en una herramienta profesional para crear conjuntos de datos de entrenamiento de IA para el diseño de patrones.

-   **Panel de Propiedades y Exportación de Datos para IA:**
    -   Un nuevo **Panel de Propiedades** te permite añadir metadatos ricos y semánticos a tus diseños.
    -   **Etiquetas Globales:** Define un `Nombre de Pieza` y `Talla` para el patrón completo.
    -   **Etiquetas de Nodo:** Asigna etiquetas alfanuméricas (ej: 'A', '1') y descripciones a los puntos clave. Las etiquetas se muestran directamente en el lienzo.
    -   **Etiquetas de Segmento:** Añade descripciones a los segmentos del trazado (ej: "Costura Lateral", "Sisa").
    -   **Exportación Inteligente de SVG:** Todos estos metadatos se incrustan como un objeto JSON limpio dentro del SVG exportado, creando patrones "inteligentes" listos para los pipelines de entrenamiento de IA.

-   **Herramientas de Medición de Precisión:**
    -   **Mostrar/Ocultar Medidas:** Un nuevo botón en la barra de herramientas te permite mostrar u ocultar la longitud precisa (en cm) de cada segmento de tu trazado.
    -   **Feedback en Vivo:** Mientras dibujas una nueva línea o arrastras un punto, una medida en tiempo real aparece junto a tu cursor, mostrando la longitud o distancia exacta.

-   **Formas Primitivas:**
    -   Genera instantáneamente formas base comunes.
    -   Crea **Cuadrados, Rombos y Círculos** con dimensiones personalizadas a través de un simple diálogo.

## Características

-   **Modos de Edición Dual:** Cambia entre **Modo Patrón** (para trabajo estructural con líneas rectas) y **Modo Bézier** (para el refinamiento de curvas).
-   **Panel de Etiquetado de Datos:** Asigna propiedades como Nombre de Pieza, Talla y etiquetas/descripciones personalizadas a nodos y segmentos.
-   **Exportación Inteligente de SVG:** Exporta trazados con todos los metadatos incrustados como un objeto JSON estructurado, listo para pipelines de IA/ML.
-   **Herramientas de Medición:** Activa la visualización en el lienzo de las longitudes de los segmentos y ve medidas en tiempo real al editar.
-   **Formas Primitivas:** Crea instantáneamente cuadrados, rombos o círculos con las dimensiones especificadas.
-   **Aplicar Simetría:** Crea formas perfectamente simétricas reflejando un trazado cerrado a través de una arista recta seleccionada.
-   **Manipulación de Trazados:** Control total sobre nodos, curvas y segmentos.
-   **Deshacer y Rehacer (Undo/Redo):** Un sistema de historial robusto que rastrea todos los cambios, incluidas las ediciones de etiquetas.
-   **Ajuste a la Rejilla, Paneo y Zoom:** Navegación y control de lienzo profesional estándar.
-   **Exportar a SVG:** Exporta tu creación como un archivo `.svg` limpio y rico en datos.

## Cómo Usarlo

1.  **Inicia un Proyecto:** Usa las **Formas Primitivas** (Cuadrado, etc.) para empezar con una base, o comienza a dibujar en **Modo Patrón**.
2.  **Estructura y Refina:** Usa el **Modo Patrón** para el contorno básico con líneas rectas. Cambia a **Modo Bézier** para perfeccionar las curvas.
3.  **Etiqueta tus Datos:**
    -   Abre el **Panel de Propiedades**.
    -   Sin nada seleccionado, introduce el **Nombre de Pieza** y la **Talla** globales.
    -   Haz clic en un nodo (punto de ancla) para darle una **Etiqueta** y una **Descripción**.
    -   Haz clic en un segmento de línea para añadir una **Descripción del Segmento**.
4.  **Verifica las Dimensiones:**
    -   Haz clic en el botón **"Mostrar/Ocultar Medidas"** para verificar las longitudes de todos los segmentos.
    -   Observa la información de medidas en tiempo real mientras arrastras puntos para hacer ajustes precisos.
5.  **Aplica Simetría:** Para piezas simétricas, cierra el trazado, haz clic en **"Aplicar Simetría"** y selecciona una arista recta para reflejar el objeto.
6.  **Navega:** Usa la **rueda del ratón** para hacer zoom y la **barra espaciadora + arrastrar** para panear. Haz **clic derecho** para deseleccionar cualquier elemento activo.
7.  **Exporta:** Haz clic en **"Exportar a SVG"** para guardar tu patrón. El archivo resultante contendrá tanto el trazado visual como todos los metadatos que introdujiste, listo para tu proyecto de IA.
