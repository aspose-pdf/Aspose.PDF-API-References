---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Drawing.Graph. Representa un párrafo generador de gráficos.
type: docs
weight: 3940
url: /es/net/aspose.pdf.drawing/graph/
---
## Clase Graph

Representa un párrafo generador de gráficos.

```csharp
public sealed class Graph : BaseParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Inicializa una nueva instancia de la clase `Graph`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Obtiene o establece el borde. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Obtiene o establece un objeto [`GraphInfo`](./graphinfo/) que indica la información del gráfico, como color, ancho de línea, etc. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Obtiene o establece un valor de punto flotante que indica la altura del gráfico. La unidad es punto. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del párrafo. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Obtiene o establece el cambio de posición actual después de procesar el párrafo. (por defecto verdadero) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor por defecto es falso. (para la generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si el párrafo es en línea. El valor por defecto es falso. (para la generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor por defecto es falso. (para la generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor por defecto es falso. (para la generación de pdf) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Obtiene o establece la coordenada izquierda de la tabla. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf). |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Obtiene o establece una colección [`Shapes`](./shapes/) que indica todas las formas en el gráfico. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Obtiene o establece un valor de cadena que indica el título del gráfico. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Obtiene o establece la coordenada superior de la tabla. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Obtiene o establece un valor de punto flotante que indica el ancho del gráfico. La unidad es punto. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor entero que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Clona el gráfico. |

### Ver También

* clase [BaseParagraph](../../aspose.pdf/baseparagraph/)
* espacio de nombres [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* ensamblaje [Aspose.PDF](../../)