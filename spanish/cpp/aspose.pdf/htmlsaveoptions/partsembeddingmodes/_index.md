---
title: "Aspose::Pdf::HtmlSaveOptions::PartsEmbeddingModes enumeración"
linktitle: "PartsEmbeddingModes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::PartsEmbeddingModes enumeración. Esta enumeración enumera los posibles modos de incrustación de archivos referenciados en HTML. Permite controlar si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas en C++."
type: docs
weight: 5800
url: /es/cpp/aspose.pdf/htmlsaveoptions/partsembeddingmodes/
---
## PartsEmbeddingModes enum


Este enum enumera los modos posibles de incrustación de archivos referenciados en HTML. Permite controlar si los archivos referenciados (HTML, fuentes, imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas.

```cpp
enum class PartsEmbeddingModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| EmbedAllIntoHtml | 0 | Forza la incrustación de todos los archivos referenciados (Css, Imágenes, Fuentes) en el marcado HTML generado (es decir, en el propio HTML). Este enfoque genera un solo archivo HTML, pero el tamaño total de la salida se vuelve mayor (porque se utiliza codificación Base64 de los binarios) y no todos los navegadores (especialmente los heredados) procesan correctamente los binarios incrustados en HTML. Pero permite obtener un HTML que contiene todo el resultado, sin archivos adicionales. |
| EmbedCssOnly | 1 | Forza la separación de todos los archivos referenciados excepto CSS (Imágenes y Fuentes). Es decir, CSS se incrustará en el HTML resultante, y todos los demás archivos referenciados (Imágenes y Fuentes) se procesarán como partes externas. Genera un HTML que es adecuado para un amplio conjunto de navegadores. |
| NoEmbedding | 2 | Forza la separación de los archivos referenciados (Css, Imágenes, Fuentes). Este enfoque genera un conjunto de archivos, pero el tamaño total de la salida se vuelve más pequeño (porque no se utiliza codificación Base64 de los binarios). Además, este enfoque genera un HTML que es adecuado para un amplio conjunto de navegadores. |

## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
