---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator. Representa una clase para generar una representación en markdown de las diferencias de textos. Debido a la sintaxis de markdown, no es posible mostrar cambios en los caracteres de espacio en blanco. La selección de cambios hace que se agreguen caracteres de espacio en blanco alrededor del formato, de lo contrario, el visor de markdown no mostrará correctamente el texto. Los saltos de línea eliminados se indican con el símbolo de párrafo.
type: docs
weight: 3250
url: /es/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## Clase MarkdownDiffOutputGenerator

Representa una clase para generar una representación en markdown de las diferencias de textos. Debido a la sintaxis de markdown, no es posible mostrar cambios en los caracteres de espacio en blanco. La selección de cambios hace que se agreguen caracteres de espacio en blanco alrededor del formato, de lo contrario, el visor de markdown no mostrará correctamente el texto. Los saltos de línea eliminados se indican con el símbolo de párrafo.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | El constructor por defecto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |

### Ver También

* interfaz [IFileOutputGenerator](../ifileoutputgenerator/)
* interfaz [IStringOutputGenerator](../istringoutputgenerator/)
* espacio de nombres [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* ensamblado [Aspose.PDF](../../)