---
title: "Aspose::Pdf::EpubSaveOptions::RecognitionMode enumeración"
linktitle: "RecognitionMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::EpubSaveOptions::RecognitionMode enumeración. Cuando un archivo PDF (que normalmente tiene diseño fijo) se está convirtiendo, el motor de conversión intenta realizar agrupamiento y análisis multinivel para restaurar la intención original del autor del documento y producir un resultado en diseño fluido. Esta propiedad ajusta esa conversión para el método deseado de reconocimiento de contenido en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf/epubsaveoptions/recognitionmode/
---
## RecognitionMode enum


Cuando un archivo PDF (que normalmente tiene un diseño fijo) se está convirtiendo, el motor de conversión intenta realizar agrupamiento y análisis multinivel para restaurar la intención original del autor del documento y producir el resultado en un diseño fluido. Esta propiedad ajusta esa conversión para este u otro método deseable de reconocimiento de contenido.

```cpp
enum class RecognitionMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Flow | 0 | Modo de reconocimiento completo, el motor intenta realizar agrupamiento y análisis multinivel para restaurar la intención original del autor del documento y producir XHTML en diseño fluido. |
| PdfFlow | 1 | La idea principal de esta conversión se basa en guardar el orden "natural" de renderizado del contenido que se forma durante el procesamiento de documentos PDF. En general, los documentos PDF mantienen un orden de renderizado de arriba a abajo y de izquierda a derecha (ver el archivo adjunto directions.png). Esta suposición permite crear un algoritmo de ruta única que transformará los elementos Aps que tienen posiciones (diseño fijo) en formatos fluidos como HTML, EPUB, DOC. Este modo será especialmente útil para convertir de PDF (APS) a EPUB, porque el formato EPUB se desarrolló para lectores electrónicos como el Kindle o los teléfonos inteligentes. El tamaño de pantalla de esos dispositivos suele ser menor que el tamaño de pantalla de una PC ordinaria. Por lo tanto, el contenido de los documentos EPUB se guarda mejor en formato fluido, para un renderizado correcto en pantallas de diferentes tamaños. En este modo, cada columna se añadirá al final de la columna anterior, lo que permite mantener la estructura lógica del documento transformado durante la "paginación" en los lectores EPUB. Este logro permite renderizar correctamente artículos científicos o de revistas. |
| Fijo | 2 | Este modo es rápido y bueno para preservar al máximo la apariencia original de las páginas, pero desafortunadamente muchos lectores EPUB no admiten XHTML con diseño fijo. |

## Ver también

* Class [EpubSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
