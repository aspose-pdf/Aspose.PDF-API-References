---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. Clase para especificar parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante en unidades de espacio predeterminadas o en porcentajes del tamaño de las páginas iniciales; márgenes Izquierdo, Superior, Inferior y Derecho en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; Algunos valores pueden dejarse nulos para cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores explícitamente especificados.  Esta clase se utiliza en el método ResizeContents.
type: docs
weight: 4480
url: /es/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Clase para especificar parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño de las páginas iniciales; márgenes Izquierdo, Superior, Inferior y Derecho en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; Algunos valores pueden dejarse nulos para cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores explícitamente especificados. Por ejemplo: si el ancho de la página = 100 y el nuevo ancho de la página especificado es 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se utiliza en el método ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Crea parámetros de redimensionamiento donde todos los valores se establecen en "auto". Más tarde, los márgenes y el tamaño del contenido pueden especificarse si es necesario. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crea parámetros de redimensionamiento con valores de margen y tamaño de contenido especificados. |

## Properties

| Name | Description |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Obtiene o establece el margen inferior en la página resultante. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Obtiene o establece la altura del contenido de la página fuente en la página resultante. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Obtiene o establece el ancho del contenido de la página fuente en la página resultante. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Obtiene o establece el margen izquierdo en la página resultante. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Obtiene o establece el margen derecho en la página resultante. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Obtiene o establece el margen superior en la página resultante. |

## Methods

| Name | Description |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Crea parámetros de redimensionamiento con el tamaño de contenido especificado. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Crea parámetros de redimensionamiento con el tamaño de contenido especificado en porcentajes del tamaño de la página inicial. Los márgenes se calculan automáticamente. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Crea parámetros de redimensionamiento con valores de márgenes especificados. El tamaño del contenido se calcula automáticamente. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Crea parámetros de redimensionamiento. Los márgenes se especifican en porcentajes del tamaño de la página inicial. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Crea parámetros de redimensionamiento para el redimensionamiento de la página. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Crea parámetros de redimensionamiento para el redimensionamiento de la página. Los nuevos tamaños se especifican en porcentaje. |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)