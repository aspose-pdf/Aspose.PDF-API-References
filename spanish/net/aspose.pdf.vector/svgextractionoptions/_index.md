---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Vector.SvgExtractionOptions. Representa una clase de opciones para extraer gráficos vectoriales de la página del documento pdf
type: docs
weight: 11240
url: /es/net/aspose.pdf.vector/svgextractionoptions/
---
## Clase SvgExtractionOptions

Representa una clase de opciones para extraer gráficos vectoriales de la página del documento pdf.

```csharp
public class SvgExtractionOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Obtiene y establece la opción para agrupar automáticamente subrutas en imágenes. Esta opción excluye la opción [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Obtiene y establece la opción para extraer cada subruta de un documento PDF a imágenes SVG separadas. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Obtiene y establece el rectángulo delimitador que define el área de extracción para la extracción SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Obtiene y establece una opción de la fuerza de agrupamiento de subrutas en imágenes. Permite configurar el grado de agrupamiento de subrutas. El rango de valores es de 0 a 1. Un valor de 0 corresponde a la opción [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) habilitada. Un valor de 1 creará una única imagen para todos los caminos vectoriales en la página. La opción tiene efecto cuando [`AutoGrouping`](./autogrouping/) es falso. El valor predeterminado es `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Obtiene o establece el ancho de trazo mínimo que se utilizará en el SVG resultante. Si el PDF utiliza un ancho de trazo más delgado, se reemplazará con este ancho. El valor predeterminado es 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Obtiene y establece una opción para definir estrictamente si las subrutas están dentro del rectángulo especificado en [`ExtractionAreaBound`](./extractionareabound/). Si se establece en falso, entonces las subrutas que no están completamente incluidas en [`ExtractionAreaBound`](./extractionareabound/) serán extraídas. El valor predeterminado es `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Obtiene y establece una bandera que determina si los XForm encontrados en las páginas deben ser descompactados o no. Los elementos XFrom pueden terminar en diferentes archivos SVG. Solo se descompactan los XForms que son renderizados por declaraciones Do del contenido de la página. Los XForms anidados no se descompactan. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Obtiene y establece la opción para descompactar solo el XForm correspondiente al predicado especificado. |

### Ver También

* espacio de nombres [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* ensamblaje [Aspose.PDF](../../)