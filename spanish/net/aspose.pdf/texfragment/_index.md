---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.TeXFragment. Representa un fragmento TeX
type: docs
weight: 10360
url: /es/net/aspose.pdf/texfragment/
---
## Clase TeXFragment

Representa un fragmento TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | Inicializa una nueva instancia de la clase HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | Inicializa una nueva instancia de la clase HtmlFragment. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del párrafo |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del fragmento (para generador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si el párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor bool que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor bool que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Obtiene o establece las opciones de carga de TeX que se utilizarán para cargar (y renderizar) LaTeX en esta instancia de la clase. Utilícelo cuando sea necesario usar una configuración específica para la importación de LaTeX para esta o aquella instancia (por ejemplo, cuando esta o aquella instancia deba usar una BasePath específica para LaTeX importado o deba usar un cargador específico de recursos externos). Si el parámetro es predeterminado (null), se utilizarán las opciones de carga estándar de LaTeX. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del párrafo |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Clona el fragmento. |

### Ver También

* clase [FormattedFragment](../formattedfragment/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)