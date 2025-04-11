---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum EpubSaveOptionsRecognitionMode de Aspose.Pdf. Cuando se convierte un archivo PDF que generalmente tiene un diseño fijo, el motor de conversión intenta realizar agrupamiento y análisis multilevel para restaurar la intención original del autor del documento y producir un resultado en diseño fluido. Esta propiedad ajusta esa conversión para este o aquel método deseable de reconocimiento de contenido.
type: docs
weight: 4070
url: /es/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## Enumeración EpubSaveOptions.RecognitionMode

Cuando se convierte un archivo PDF (que generalmente tiene un diseño fijo), el motor de conversión intenta realizar agrupamiento y análisis multilevel para restaurar la intención original del autor del documento y producir un resultado en diseño fluido. Esta propiedad ajusta esa conversión para este o aquel método deseable de reconocimiento de contenido.

```csharp
public enum RecognitionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Fluido | `0` | Modo de reconocimiento completo, el motor intenta realizar agrupamiento y análisis multilevel para restaurar la intención original del autor del documento y producir xhtml en diseño fluido. |
| PdfFluido | `1` | La idea principal de esta conversión se basa en guardar el orden "natural" de renderizado del contenido que se forma durante el procesamiento de documentos pdf. En los casos generales, los documentos pdf mantienen un orden de renderizado de arriba hacia abajo y de izquierda a derecha (ver dirección adjunta directions.png). Esta suposición permite crear un algoritmo de un solo camino que transformará los elementos Aps que tienen posiciones (diseño fijo) en formatos de flujo como HTML, EPUB, DOC. Este modo será especialmente útil para convertir de PDF(APS) a EPUB, porque el formato EPUB fue desarrollado para lectores electrónicos como el Kindle o teléfonos inteligentes. El tamaño de pantalla de esos dispositivos suele ser menor que el tamaño de pantalla de una PC ordinaria. Por lo tanto, es mejor guardar el contenido de los documentos EPUB en formato de flujo, para un renderizado correcto en pantallas de diferentes tamaños. En este modo, cada columna se añadirá al final de la columna anterior, lo que permite mantener la estructura lógica del documento transformado durante la "paginación" en los lectores EPUB. Este logro permite renderizar correctamente artículos científicos o de revistas. |
| Fijo | `2` | Este modo es rápido y bueno para preservar al máximo la apariencia original de las páginas, pero desafortunadamente muchos lectores EPUB no soportan xhtml con diseño fijo. |

### Ver También

* clase [EpubSaveOptions](../epubsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)