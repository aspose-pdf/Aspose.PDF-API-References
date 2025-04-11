---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextSegment. Representa un segmento de texto en Pdf
type: docs
weight: 11050
url: /es/net/aspose.pdf.text/textsegment/
---
## Clase TextSegment

Representa un segmento de texto en Pdf.

```csharp
public sealed class TextSegment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Crea un objeto TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | Crea un objeto TextSegment. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Obtiene la posición del texto para el texto, representado con el objeto `TextSegment`. La YIndent de la estructura Position representa la coordenada de línea base del segmento de texto. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Obtiene la colección de objetos CharInfo que representan información sobre los caracteres en el segmento de texto. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Obtiene el índice del carácter final del segmento actual en el operador de texto mostrar (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Obtiene o establece el hipervínculo del segmento (para generador de pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Obtiene la posición del texto para el texto, representado con el objeto `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Obtiene el rectángulo del TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Obtiene el índice del carácter inicial del segmento actual en el operador de texto mostrar (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Obtiene o establece el objeto de texto String que representa el objeto `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Obtiene o establece el estado del texto para el texto que representa el objeto `TextSegment`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Codifica la cadena como html. |

## Observaciones

En pocas palabras, los objetos `TextSegment` son hijos del objeto [`TextFragment`](../textfragment/). En detalle: El texto del documento pdf en Pdf está representado por dos objetos básicos: [`TextFragment`](../textfragment/) y `TextSegment`. Las diferencias entre ellos dependen en gran medida del contexto. Consideremos el siguiente escenario. El usuario busca el texto "hello world" para operar con él, cambiar sus propiedades, mirar, etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

La representación física del texto en pdf es muy compleja. El texto "hello world" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto de Aspose.Pdf establece básicamente que el objeto [`TextFragment`](../textfragment/) proporciona un conjunto de operaciones lógicas único sobre el conjunto de objetos `TextSegment` físicos que representan la consulta del usuario. En el escenario de búsqueda de texto, [`TextFragment`](../textfragment/) es la representación lógica del texto "hello world", y la colección de objetos `TextSegment` representa todos los segmentos físicos que construyen el objeto de texto "hello world". Así, [`TextFragment`](../textfragment/) está cerca de la representación lógica del texto. Y `TextSegment` está cerca de la representación física del texto. Obviamente, cada objeto `TextSegment` puede tener su propia fuente, color, propiedades de posicionamiento. [`TextFragment`](../textfragment/) proporciona una forma simple de cambiar el texto con sus propiedades: establecer fuente, establecer tamaño de fuente, establecer color de fuente, etc. Mientras tanto, los objetos `TextSegment` son accesibles y los usuarios pueden operar con los objetos `TextSegment` de forma independiente.

## Ejemplos

El ejemplo demuestra cómo cambiar el color del texto y el tamaño de la fuente del texto con el objeto [`TextState`](./textstate/) del objeto `TextSegment`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)