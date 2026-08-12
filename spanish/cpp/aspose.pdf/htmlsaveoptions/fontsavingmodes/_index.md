---
title: "Aspose::Pdf::HtmlSaveOptions::FontSavingModes enumeración"
linktitle: "FontSavingModes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::FontSavingModes enumeración. Enumera los modos que pueden usarse para guardar las fuentes referenciadas en el PDF guardado en C++."
type: docs
weight: 5300
url: /es/cpp/aspose.pdf/htmlsaveoptions/fontsavingmodes/
---
## FontSavingModes enum


Enumera los modos que pueden usarse para guardar fuentes referenciadas en el PDF guardado.

```cpp
enum class FontSavingModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AlwaysSaveAsWOFF | 0 | Todas las fuentes referenciadas se guardarán y referenciarán como fuentes WOFF. |
| AlwaysSaveAsTTF | 1 | Todas las fuentes referenciadas se guardarán y referenciarán como fuentes TTF. |
| AlwaysSaveAsEOT | 2 | Todas las fuentes referenciadas se guardarán y referenciarán como EOT-fonts. |
| SaveInAllFormats | 3 | Todas las fuentes referenciadas se guardarán (y referenciarán en CSS) como 3 archivos independientes: EOT, TTH, WOFF. Incrementa el tamaño de los datos de salida pero hace que la salida sea adecuada para la gran mayoría de los navegadores web. |
| DontSave | 4 | No se guardarán las fuentes referenciadas. |

## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
