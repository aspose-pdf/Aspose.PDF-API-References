---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextFragment. Representa un fragmento de texto en Pdf
type: docs
weight: 10940
url: /es/net/aspose.pdf.text/textfragment/
---
## Clase TextFragment

Representa un fragmento de texto en Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | Inicializa una nueva instancia del objeto `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | Crea un objeto `TextFragment` con un solo objeto [`TextSegment`](../textsegment/) dentro. Especifica la cadena de texto dentro del segmento. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | Inicializa una nueva instancia del objeto `TextFragment` con posiciones de [`TabStops`](../tabstops/) predefinidas. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | Crea un objeto `TextFragment` con un solo objeto [`TextSegment`](../textsegment/) dentro y posiciones de [`TabStops`](../tabstops/) predefinidas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Obtiene la posición del texto para el texto, representado con el objeto `TextFragment`. El YIndent de la estructura Position representa la coordenada de la línea base del fragmento de texto. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Obtiene o establece la nota al final del párrafo. (solo para generación de pdf) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Obtiene o establece la nota al pie del párrafo. (solo para generación de pdf) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Obtiene el objeto de formulario que contiene el TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Obtiene o establece una alineación horizontal del fragmento de texto. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Establece el hipervínculo del fragmento |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtiene o establece un valor booleano que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para generación de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtiene o establece si un párrafo es en línea. El valor predeterminado es falso. (para generación de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtiene o establece un valor booleano que obliga a que este párrafo se genere en una nueva página. El valor predeterminado es falso. (para generación de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es falso. (para generación de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Obtiene la página que contiene el TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Obtiene o establece la posición del texto para el texto, representado con el objeto `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Obtiene el rectángulo del TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto/largo. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Obtiene los segmentos de texto para el `TextFragment` actual. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Obtiene o establece el objeto de texto String que representa el objeto `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no se puede escribir con la fuente. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Obtiene o establece el estado del texto para el texto que representa el objeto `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Obtiene o establece una alineación vertical del fragmento de texto. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Obtiene o establece el conteo de líneas de ajuste para este párrafo (solo para generación de pdf) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtiene o establece un valor entero que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | Clona el fragmento. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | Clona el fragmento con todos los segmentos. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Obtiene los [`TextSegment`](../textsegment/)(s) que representan la parte especificada del texto del `TextFragment`. |

## Observaciones

En pocas palabras, el objeto `TextFragment` contiene una lista de objetos [`TextSegment`](../textsegment/). En detalle: El texto del documento pdf en Pdf está representado por dos objetos básicos: `TextFragment` y [`TextSegment`](../textsegment/). Las diferencias entre ellos son principalmente dependientes del contexto. Consideremos el siguiente escenario. El usuario busca el texto "hello world" para operar con él, cambiar sus propiedades, mirar, etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La representación física del texto en pdf es muy compleja. El texto "hello world" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto de Aspose.Pdf establece básicamente que el objeto `TextFragment` proporciona un conjunto de operaciones lógicas sobre el conjunto de objetos físicos [`TextSegment`](../textsegment/) que representan la consulta del usuario. En el escenario de búsqueda de texto, `TextFragment` es la representación lógica del texto "hello world", y la colección de objetos [`TextSegment`](../textsegment/) representa todos los segmentos físicos que construyen el objeto de texto "hello world". Por lo tanto, `TextFragment` está cerca de la representación lógica del texto. Y [`TextSegment`](../textsegment/) está cerca de la representación física del texto. Obviamente, cada objeto [`TextSegment`](../textsegment/) puede tener su propia fuente, color y propiedades de posicionamiento. `TextFragment` proporciona una forma sencilla de cambiar el texto con sus propiedades: establecer fuente, establecer tamaño de fuente, establecer color de fuente, etc. Mientras tanto, los objetos [`TextSegment`](../textsegment/) son accesibles y los usuarios pueden operar con los objetos [`TextSegment`](../textsegment/) de forma independiente. Tenga en cuenta que cambiar las propiedades de TextFragment puede cambiar la colección interna [`Segments`](./segments/) porque TextFragment es un objeto agregado y puede reorganizar segmentos internos o fusionarlos en un solo segmento. Si su requisito es dejar la colección [`Segments`](./segments/) sin cambios, cambie los segmentos internos individualmente.

## Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* clase [BaseParagraph](../../aspose.pdf/baseparagraph/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)