---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsPartsEmbeddingModes de Aspose.Pdf. Este enum enumera los posibles modos de incrustación de archivos referenciados en HTML. Permite controlar si los archivos referenciados (HTML, Fuentes, Imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas.
type: docs
weight: 5710
url: /es/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## Enumeración HtmlSaveOptions.PartsEmbeddingModes

Este enum enumera los posibles modos de incrustación de archivos referenciados en HTML. Permite controlar si los archivos referenciados (HTML, Fuentes, Imágenes, CSS) se incrustarán en el archivo HTML principal o se generarán como entidades binarias separadas.

```csharp
public enum PartsEmbeddingModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Obliga a incrustar todos los archivos referenciados (CSS, Imágenes, Fuentes) en el marcado HTML generado (es decir, en el propio HTML). Este enfoque genera un archivo HTML, pero el tamaño total de la salida se vuelve más grande (debido a que se utiliza la codificación Base64 de los binarios) y no todos los navegadores (especialmente los antiguos) procesan con éxito los binarios incrustados en HTML. Pero permite obtener HTML que contiene todo el resultado, sin archivos adicionales. |
| EmbedCssOnly | `1` | Obliga a dejar aparte todos los archivos referenciados excepto CSS (Imágenes y Fuentes). Es decir, CSS se incrustará en el HTML resultante, y todos los demás archivos referenciados (Imágenes y Fuentes) se procesarán como partes externas. Genera HTML que es adecuado para un amplio conjunto de navegadores. |
| NoEmbedding | `2` | Obliga a dejar aparte los archivos referenciados (CSS, Imágenes, Fuentes). Este enfoque genera un conjunto de archivos, pero el tamaño total de la salida se vuelve más pequeño (debido a que no se utiliza la codificación Base64 de los binarios). Además, este enfoque genera HTML que es adecuado para un amplio conjunto de navegadores. |

### Véase también

* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)