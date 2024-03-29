---
title: EpubSaveOptions.RecognitionMode
second_title: Referencia de API de Aspose.PDF para .NET
description: Cuando se convierte un archivo PDF que generalmente tiene un diseño fijo el motor de conversión intenta agrupar y analizar varios niveles para restaurar la intención del autor del documento original y producir un diseño de flujo. Esta propiedad ajusta esa conversión para este o ese método deseable de reconocimiento de contenido.
type: docs
weight: 2110
url: /es/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

Cuando se convierte un archivo PDF (que generalmente tiene un diseño fijo), el motor de conversión intenta agrupar y analizar varios niveles para restaurar la intención del autor del documento original y producir un diseño de flujo. Esta propiedad ajusta esa conversión para este o ese método deseable de reconocimiento de contenido.

```csharp
public enum RecognitionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Flow | `0` | Modo de reconocimiento completo, el motor intenta agrupar y analizar varios niveles para restaurar la intención del autor del documento original y producir xhtml en el diseño de flujo. |
| PdfFlow | `1` | La idea principal de esta conversión se basa en guardar el orden "natural" de representación del contenido que se forma durante el procesamiento de documentos pdf. En los casos generales, los documentos pdf mantienen el orden de representación de arriba hacia abajo\izquierda-derecha (consulte las direcciones adjuntas.png ). Esta suposición permite to crear un algoritmo de ruta única que transformará los elementos Aps que tienen posiciones (diseño fijo) en formatos de flujo como HTML, EPUB, DOC. Este modo será especialmente útil para convertir de PDF (APS) a EPUB, porque el formato EPUB se desarrolló para lectores electrónicos como Kindle o teléfonos inteligentes. El tamaño de la pantalla de esos dispositivos suele ser menor que el tamaño de la pantalla de una PC ordinaria. Por lo tanto, es mejor guardar el contenido de los documentos EPUB en el formato de flujo, para una representación correcta en pantallas con diferentes tamaños. En este modo, cada columna se agregará al final de la columna anterior, lo que permite mantener la estructura lógica del documento transformado durante "paginación" en los lectores de EPUB. Este logro permite renderizar correctamente artículos científicos o de revistas. |
| Fixed | `2` | Este modo es rápido y bueno para preservar al máximo el aspecto original de las páginas, pero desafortunadamente muchos lectores de EPUB no admiten xhtml con diseño fijo |

### Ver también

* class [EpubSaveOptions](../epubsaveoptions)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
