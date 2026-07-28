---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Este enum enumera los posibles modos de incrustación de archivos referenciados en HTML. Permite controlar si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el principal."
type: docs
weight: 2130
url: /es/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Este enum enumera los modos posibles de incrustación de archivos referenciados en HTML. Permite controlar si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas.

## Campos

| Campo | Descripción |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Forza la incrustación de todos los archivos referenciados (Css, Imágenes, Fuentes) en el marcado HTML generado (es decir, en el propio HTML). Este enfoque genera un único archivo HTML, pero el tamaño total de la salida se vuelve mayor (porque se utiliza codificación Base64 de los binarios) y no todos los navegadores (especialmente los heredados) procesan correctamente los binarios incrustados en HTML. Pero permite obtener un HTML que contiene todo el resultado, sin archivos adicionales. |
| [EmbedCssOnly](#EmbedCssOnly) | Forza la separación de todos los archivos referenciados excepto CSS (Imágenes y Fuentes). Es decir, el CSS se incrustará en el HTML resultante, y todos los demás archivos referenciados (Imágenes y Fuentes) se procesarán como partes externas. Genera un HTML que es adecuado para un amplio conjunto de navegadores. |
| [NoEmbedding](#NoEmbedding) | Forza la separación de los archivos referenciados (Css, Imágenes, Fuentes). Este enfoque genera un conjunto de archivos, pero el tamaño total de la salida se vuelve menor (porque no se utiliza codificación Base64 de los binarios). Además, este enfoque genera un HTML que es adecuado para un amplio conjunto de navegadores. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Forza la incrustación de todos los archivos referenciados (Css, Imágenes, Fuentes) en el marcado HTML generado (es decir, en el propio HTML). Este enfoque genera un único archivo HTML, pero el tamaño total de la salida se vuelve mayor (porque se utiliza codificación Base64 de los binarios) y no todos los navegadores (especialmente los heredados) procesan correctamente los binarios incrustados en HTML. Pero permite obtener un HTML que contiene todo el resultado, sin archivos adicionales.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Forza la separación de todos los archivos referenciados excepto CSS (Imágenes y Fuentes). Es decir, el CSS se incrustará en el HTML resultante, y todos los demás archivos referenciados (Imágenes y Fuentes) se procesarán como partes externas. Genera un HTML que es adecuado para un amplio conjunto de navegadores.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Forza la separación de los archivos referenciados (Css, Imágenes, Fuentes). Este enfoque genera un conjunto de archivos, pero el tamaño total de la salida se vuelve menor (porque no se utiliza codificación Base64 de los binarios). Además, este enfoque genera un HTML que es adecuado para un amplio conjunto de navegadores.
