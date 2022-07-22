---
title: TextSegment
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa un segmento de texto PDF.
type: docs
weight: 7210
url: /es/net/aspose.pdf.text/textsegment/
---
## TextSegment class

Representa un segmento de texto PDF.

```csharp
public sealed class TextSegment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextSegment](textsegment#constructor)() | Crea el objeto TextSegment. |
| [TextSegment](textsegment#constructor_1)(string) | Crea el objeto TextSegment. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | Obtiene la posición del texto, representada con[`TextSegment`](../textsegment) objeto. La sangría Y de la estructura Posición representa la coordenada de línea base del segmento de texto. |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | Obtiene una colección de objetos CharInfo que representan información sobre los caracteres en el segmento de texto. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | Obtiene el índice de carácter final del segmento actual en el segmento del operador de mostrar texto (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | Obtiene o establece el hipervínculo del segmento (para el generador de pdf). |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | Obtiene la posición del texto, representada con[`TextSegment`](../textsegment) objeto. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | Obtiene el rectángulo del TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | Obtiene el índice de carácter inicial del segmento actual en el segmento del operador de mostrar texto (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | Obtiene o estableceString objeto de texto que el[`TextSegment`](../textsegment) objeto representa. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | Obtiene o establece opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no se puede escribir con font. |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | Obtiene o establece el estado de texto para el texto que[`TextSegment`](../textsegment) objeto representa. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | Codifica la cadena como html. |

### Observaciones

En pocas palabras,[`TextSegment`](../textsegment) los objetos son hijos de[`TextFragment`](../textfragment) objeto. En detalle: Texto del documento pdf enPdf está representado por dos objetos básicos:[`TextFragment`](../textfragment) y[`TextSegment`](../textsegment) Las diferencias entre ellos dependen principalmente del contexto. Consideremos el siguiente escenario. El usuario busca el texto "hola mundo" para operar con él, cambiar sus propiedades, buscar, etc. La representación del texto pdf físicamente es muy compleja. El texto "hola mundo" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto Aspose.Pdf básicamente establece que[`TextFragment`](../textfragment) object proporciona una operación lógica única establecida sobre física[`TextSegment`](../textsegment) conjunto de objetos que representan la consulta del usuario. En el escenario de búsqueda de texto,[`TextFragment`](../textfragment) es la representación de texto lógica "hola mundo", y[`TextSegment`](../textsegment)la colección de objetos representa todos los segmentos físicos que construyen el objeto de texto "hola mundo". Entonces,[`TextFragment`](../textfragment) está cerca de la representación de texto lógico. Y[`TextSegment`](../textsegment) está cerca de la representación de texto físico. Obviamente cada[`TextSegment`](../textsegment) el objeto puede tener su propia fuente, color, propiedades de posicionamiento. [`TextFragment`](../textfragment) proporciona una forma sencilla de cambiar el texto con sus propiedades: establecer fuente, establecer tamaño de fuente, establecer color de fuente, etc. Mientras tanto[`TextSegment`](../textsegment) los objetos son accesibles y los usuarios pueden operar con[`TextSegment`](../textsegment) objetos independientemente.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### Ejemplos

El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con[`TextState`](./textstate) objeto de[`TextSegment`](../textsegment) objeto.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambiar el color de primer plano del primer segmento de texto de la primera aparición de texto
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Cambiar el tamaño de fuente del primer segmento de texto de la primera aparición de texto
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
