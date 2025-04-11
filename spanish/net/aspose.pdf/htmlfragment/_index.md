---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.HtmlFragment. Representa un fragmento html
type: docs
weight: 5520
url: /es/net/aspose.pdf/htmlfragment/
---
## Clase HtmlFragment

Representa un fragmento html.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Inicializa una nueva instancia de la clase HtmlFragment. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del párrafo |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Obtiene o establece HtmlLoadOptions que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase. Por favor, utilícelo cuando sea necesario usar una configuración específica para la importación de HTML para esta o aquella instancia (por ejemplo, cuando esta o aquella instancia deba usar una BasePath específica para el HTML importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se utilizarán las opciones estándar de carga de HTML. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para el generador de pdf). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Obtiene o establece el quiebre de palabras |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Obtiene o establece si el párrafo tiene margen predeterminado, de lo contrario el margen es 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Obtiene el rectángulo del HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Obtiene o establece la fuente |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Clona el fragmento html. |

### Ver También

* clase [FormattedFragment](../formattedfragment/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)