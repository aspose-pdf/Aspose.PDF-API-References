---
title: PdfFileEditor.ContentsResizeParameters
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase para especificar parámetros de cambio de tamaño de página. Permite establecer los siguientes parámetros Tamaño de la página de resultados ancho alto en unidades de espacio predeterminadas o en porcentajes del tamaño de las páginas iniciales Márgenes izquierdo superior inferior y derecho en unidades de espacio predeterminadas o en porcentajes del tamaño de página inicial Algunos valores pueden dejarse nulos para el cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores explícitamente especificados. Por ejemplo si el ancho de página  100 y el nuevo ancho de página especificado 60 unidades entonces los márgenes izquierdo y derecho se calculan automáticamente 100 - 60 / 2  15. Esta clase se usa en el método ResizeContents.
type: docs
weight: 2490
url: /es/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Clase para especificar parámetros de cambio de tamaño de página. Permite establecer los siguientes parámetros: Tamaño de la página de resultados (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño de las páginas iniciales; Márgenes izquierdo, superior, inferior y derecho en unidades de espacio predeterminadas o en porcentajes del tamaño de página inicial; Algunos valores pueden dejarse nulos para el cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores explícitamente especificados. Por ejemplo: si el ancho de página = 100 y el nuevo ancho de página especificado 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se usa en el método ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ContentsResizeParameters](contentsresizeparameters#constructor)() | Crea parámetros de cambio de tamaño donde todos los valores se establecen en "auto". Si es necesario, se pueden especificar los márgenes posteriores y el tamaño del contenido. |
| [ContentsResizeParameters](contentsresizeparameters#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Crea parámetros de cambio de tamaño con valores de margen y tamaño de contenido especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/contentsresizeparameters/bottommargin) { get; set; } | Obtiene o establece el margen inferior de la página resultante. |
| [ContentsHeight](../../aspose.pdf.facades/contentsresizeparameters/contentsheight) { get; set; } | Obtiene o establece la altura del contenido de la página de origen en la página resultante. |
| [ContentsWidth](../../aspose.pdf.facades/contentsresizeparameters/contentswidth) { get; set; } | Obtiene o establece el ancho del contenido de la página de origen en la página resultante. |
| [LeftMargin](../../aspose.pdf.facades/contentsresizeparameters/leftmargin) { get; set; } | Obtiene o establece el margen izquierdo en la página resultante. |
| [RightMargin](../../aspose.pdf.facades/contentsresizeparameters/rightmargin) { get; set; } | Obtiene o establece el margen derecho de la página resultante. |
| [TopMargin](../../aspose.pdf.facades/contentsresizeparameters/topmargin) { get; set; } | Obtiene o establece el margen superior de la página resultante. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/contentsresizeparameters/contentsize)(double, double) | Crea parámetros de cambio de tamaño con el tamaño de contenido especificado. |
| static [ContentSizePercent](../../aspose.pdf.facades/contentsresizeparameters/contentsizepercent)(double, double) | Crea parámetros de cambio de tamaño con el tamaño de contenido especificado en porcentajes del tamaño de página inicial. Los márgenes se calculan automáticamente. |
| static [Margins](../../aspose.pdf.facades/contentsresizeparameters/margins)(double, double, double, double) | Crea parámetros de cambio de tamaño con un valor de márgenes especificado. El tamaño del contenido se calcula automáticamente. |
| static [MarginsPercent](../../aspose.pdf.facades/contentsresizeparameters/marginspercent)(double, double, double, double) | Crea parámetros de cambio de tamaño. Los márgenes se especifican en porcentajes del tamaño de página inicial. |
| static [PageResize](../../aspose.pdf.facades/contentsresizeparameters/pageresize)(double, double) | Crea parámetros de cambio de tamaño para el cambio de tamaño de página. |
| static [PageResizePct](../../aspose.pdf.facades/contentsresizeparameters/pageresizepct)(double, double) | Crea parámetros de cambio de tamaño para el cambio de tamaño de página. Los nuevos tamaños se especifican en porcentaje. |

### Ver también

* class [PdfFileEditor](../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
