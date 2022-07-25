---
title: TextFragment
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa fragmento de texto PDF.
type: docs
weight: 7100
url: /es/net/aspose.pdf.text/textfragment/
---
## TextFragment class

Representa fragmento de texto PDF.

```csharp
public class TextFragment : BaseParagraph
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFragment](textfragment#constructor)() | Inicializa una nueva instancia del[`TextFragment`](../textfragment) objeto. |
| [TextFragment](textfragment#constructor_2)(string) | Crea[`TextFragment`](../textfragment) objeto con solo[`TextSegment`](../textsegment) objeto dentro. Especifica la cadena de texto dentro del segmento. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Inicializa una nueva instancia del[`TextFragment`](../textfragment) objeto con predefinido[`TabStops`](../tabstops) posiciones. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Crea[`TextFragment`](../textfragment) objeto con solo[`TextSegment`](../textsegment) objeto dentro y predefinido[`TabStops`](../tabstops) posiciones. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Obtiene la posición del texto, representada con[`TextFragment`](../textfragment) object. El YIndent de la estructura Position representa la coordenada de línea base del fragmento de texto. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Obtiene o establece la nota final del párrafo (solo para generación de PDF) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Obtiene o establece la nota al pie del párrafo (solo para generación de pdf) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Obtiene el objeto de formulario que contiene el TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Obtiene o establece una alineación horizontal del fragmento de texto. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Establece el fragmento hipervínculo |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtiene o establece que un párrafo está en línea. El valor predeterminado es falso. (para la generación de PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtiene o establece un valor booleano que obliga a generar este párrafo en una nueva página. El valor predeterminado es falso. (para la generación de PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtiene o establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el párrafo siguiente. El valor predeterminado es falso. (para la generación de PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtiene o establece un margen exterior para el párrafo (para la generación de pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Obtiene la página que contiene el TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Obtiene o establece la posición del texto para el texto, representado con[`TextFragment`](../textfragment) objeto. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Obtiene el rectángulo del TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Obtiene opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por más corto/largo. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Obtiene segmentos de texto para el actual[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Obtiene o estableceString objeto de texto que el[`TextFragment`](../textfragment) objeto representa. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Obtiene o establece el estado de texto para el texto que[`TextFragment`](../textfragment) objeto representa. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Obtiene o establece una alineación vertical del fragmento de texto. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Obtiene o establece el recuento de líneas de ajuste para este párrafo (solo para generación de PDF) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtiene o establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex más grande se colocará sobre el gráfico con ZIndex más pequeño. ZIndex puede ser negativo. El gráfico con ZIndex negativo se colocará detrás del texto en la página. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Clonar el fragmento. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Clonar el fragmento con todos los segmentos. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Obtiene[`TextSegment`](../textsegment) (s) que representa una parte especificada de la[`TextFragment`](../textfragment) texto. |

### Observaciones

En pocas palabras,[`TextFragment`](../textfragment) El objeto contiene una lista de[`TextSegment`](../textsegment) objetos. En detalle: Texto del documento pdf enPdf está representado por dos objetos básicos:[`TextFragment`](../textfragment) y[`TextSegment`](../textsegment) Las diferencias entre ellos dependen principalmente del contexto. Consideremos el siguiente escenario. El usuario busca el texto "hola mundo" para operar con él, cambiar sus propiedades, buscar, etc. La representación del texto pdf físicamente es muy compleja. El texto "hola mundo" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto Aspose.Pdf básicamente establece que[`TextFragment`](../textfragment) object proporciona una operación lógica única establecida sobre física[`TextSegment`](../textsegment) conjunto de objetos que representan la consulta del usuario. En el escenario de búsqueda de texto,[`TextFragment`](../textfragment) es la representación de texto lógica "hola mundo", y[`TextSegment`](../textsegment)la colección de objetos representa todos los segmentos físicos que construyen el objeto de texto "hola mundo". Entonces,[`TextFragment`](../textfragment) está cerca de la representación de texto lógico. Y[`TextSegment`](../textsegment) está cerca de la representación de texto físico. Obviamente cada[`TextSegment`](../textsegment) el objeto puede tener su propia fuente, color, propiedades de posicionamiento. [`TextFragment`](../textfragment) proporciona una forma sencilla de cambiar el texto con sus propiedades: establecer fuente, establecer tamaño de fuente, establecer color de fuente, etc. Mientras tanto[`TextSegment`](../textsegment) los objetos son accesibles y los usuarios pueden operar con[`TextSegment`](../textsegment) objetos de forma independiente. Tenga en cuenta que cambiar las propiedades de TextFragment puede cambiar[`Segments`](./segments) colección porque TextFragment es un objeto agregado y puede reorganizar segmentos internos o fusionarlos en un solo segmento. Si su requisito es dejar el[`Segments`](./segments)colección sin cambios, cambie los segmentos internos individualmente.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Encuentra la fuente que se usará para cambiar la fuente del texto del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambia el texto y la fuente de la primera aparición de texto
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
