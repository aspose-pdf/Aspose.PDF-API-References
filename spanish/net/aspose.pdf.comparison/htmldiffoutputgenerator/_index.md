---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Comparison.HtmlDiffOutputGenerator. Representa una clase para generar la representación html de las diferencias de textos. Los saltos de línea eliminados se indican con el símbolo de párrafo.
type: docs
weight: 3200
url: /es/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## Clase HtmlDiffOutputGenerator

Representa una clase para generar la representación html de las diferencias de textos. Los saltos de línea eliminados se indican con el símbolo de párrafo.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Crea una instancia de la clase `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Crea una instancia de la clase `HtmlDiffOutputGenerator`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Obtiene y establece la cadena de estilo CSS para la operación de eliminación. Ejemplo: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Obtiene y establece la cadena de estilo CSS para la operación igual. Ejemplo: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Obtiene y establece la cadena de estilo CSS para la operación de inserción. Ejemplo: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Obtiene o establece el estilo de decoración de texto: línea a través para la operación de eliminación. El valor predeterminado es `False`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |

### Ver También

* interfaz [IFileOutputGenerator](../ifileoutputgenerator/)
* interfaz [IStringOutputGenerator](../istringoutputgenerator/)
* espacio de nombres [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* ensamblaje [Aspose.PDF](../../)