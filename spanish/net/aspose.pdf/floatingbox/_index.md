---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox class.
type: docs
weight: 4870
url: /es/net/aspose.pdf/floatingbox/
---
## Clase FloatingBox

```csharp
public class FloatingBox : BaseParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Inicializa una nueva instancia de la clase `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Inicializa una nueva instancia de la clase `FloatingBox` con el ancho y la altura especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Obtiene o establece un objeto [`Color`](../color/) que indica el color de fondo de la caja flotante. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Obtiene o establece la imagen de fondo para la página (solo para generador, no se llena al leer el documento). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Obtiene o establece un objeto [`BorderInfo`](../borderinfo/) que indica la información del borde de la caja flotante. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Obtiene o establece información de columna |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Obtiene o establece un valor float que indica la altura de la caja flotante. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del párrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para generador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor bool que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor bool que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Obtiene o establece un valor bool que indica si el párrafo necesita ser repetido en la siguiente página. El valor predeterminado es falso. El atributo solo es válido cuando el párrafo en sí y el objeto al que se refiere su ReferenceParagraphID están incluidos en RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Obtiene o establece la coordenada izquierda de la tabla. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Obtiene o establece un objeto [`MarginInfo`](../margininfo/) que indica el relleno de la caja flotante. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Obtiene o establece una colección [`Paragraphs`](./paragraphs/) que indica todos los párrafos en la celda. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Especifica la variante para determinar la ubicación de la FloatingBox en la página. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Obtiene o establece la coordenada superior de la tabla. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Obtiene o establece un valor float que indica el ancho de la caja flotante. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Clona un nuevo objeto `FloatingBox`. Los párrafos en la caja flotante no se clonan. |

### Ver También

* clase [BaseParagraph](../baseparagraph/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)