---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Constructor de TextFragmentAbsorber. Inicializa una nueva instancia de TextFragmentAbsorber que realiza la búsqueda de todos los segmentos de texto del documento o página
type: docs
weight: 10
url: /es/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Inicializa una nueva instancia de [`TextFragmentAbsorber`](../) que realiza la búsqueda de todos los segmentos de texto del documento o página.

```csharp
public TextFragmentAbsorber()
```

## Observaciones

Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

## Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Véase también

* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Inicializa una nueva instancia de [`TextFragmentAbsorber`](../) con opciones de edición de texto, que realiza la búsqueda de todos los segmentos de texto del documento o página.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opciones de edición de texto (Permite activar algunas funciones de edición). |

## Observaciones

Realiza la búsqueda de texto y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

## Ejemplos

El ejemplo demuestra cómo encontrar todos los fragmentos de texto en la primera página del documento PDF y reemplazar la fuente para ellos.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Véase también

* clase [TextEditOptions](../../texteditoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para la frase de texto especificada.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el [`TextFragmentAbsorber`](../) busca |

## Observaciones

Realiza la búsqueda de texto de la frase especificada y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

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

### Véase también

* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para el objeto de clase especificado System.Text.RegularExpressions.Regex.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | Objeto de clase System.Text.RegularExpressions.Regex que el [`TextFragmentAbsorber`](../) busca |

## Observaciones

Realiza la búsqueda de texto de la frase especificada y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

## Ejemplos

El ejemplo demuestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Véase también

* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para la frase de texto especificada y opciones de búsqueda de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el [`TextFragmentAbsorber`](../) busca |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto (Permite activar algunas funciones de búsqueda. Por ejemplo, búsqueda con expresión regular) |

## Observaciones

Realiza la búsqueda de texto de la frase especificada y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

## Ejemplos

El ejemplo demuestra cómo encontrar texto con expresión regular en la primera página del documento PDF y reemplazar el texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Véase también

* clase [TextSearchOptions](../../textsearchoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para la frase de texto especificada y opciones de búsqueda de texto.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | Objeto de clase System.Text.RegularExpressions.Regex que el [`TextFragmentAbsorber`](../) busca |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto (Permite activar algunas funciones de búsqueda.) |

## Observaciones

Realiza la búsqueda de texto de la frase especificada y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

## Ejemplos

El ejemplo demuestra cómo encontrar texto con expresión regular en la primera página del documento PDF y reemplazar el texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Véase también

* clase [TextSearchOptions](../../textsearchoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para la frase de texto especificada y opciones de búsqueda de texto.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regexes | Regex[] | Array de objetos de clase System.Text.RegularExpressions.Regex que el [`TextFragmentAbsorber`](../) busca. |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto (Permite activar algunas funciones de búsqueda.). |

## Observaciones

Realiza la búsqueda de texto del array especificado de frases y proporciona acceso a los resultados de búsqueda a través del diccionario [`RegexResults`](../regexresults/).

## Ejemplos

El ejemplo demuestra cómo encontrar texto con un array de expresiones regulares en la primera página del documento PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### Véase también

* clase [TextSearchOptions](../../textsearchoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para la frase de texto especificada, opciones de búsqueda de texto y opciones de edición de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el [`TextFragmentAbsorber`](../) busca |
| textSearchOptions | TextSearchOptions | Opciones de búsqueda de texto (Permite activar algunas funciones de búsqueda. Por ejemplo, búsqueda con expresión regular) |
| textEditOptions | TextEditOptions | Opciones de edición de texto (Permite activar algunas funciones de edición). |

## Observaciones

Realiza la búsqueda de texto de la frase especificada y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

## Ejemplos

El ejemplo demuestra cómo encontrar texto con expresión regular en la primera página del documento PDF y reemplazar el texto.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Véase también

* clase [TextSearchOptions](../../textsearchoptions/)
* clase [TextEditOptions](../../texteditoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para la frase de texto especificada y opciones de edición de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| phrase | String | Frase que el [`TextFragmentAbsorber`](../) busca |
| textEditOptions | TextEditOptions | Opciones de edición de texto (Permite activar algunas funciones de edición). |

## Observaciones

Realiza la búsqueda de texto de la frase especificada y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

### Véase también

* clase [TextEditOptions](../../texteditoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Inicializa una nueva instancia de la clase [`TextFragmentAbsorber`](../) para la frase de texto especificada y opciones de edición de texto.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | Regex | Objeto de clase System.Text.RegularExpressions.Regex que el [`TextFragmentAbsorber`](../) busca |
| textEditOptions | TextEditOptions | Opciones de edición de texto (Permite activar algunas funciones de edición). |

## Observaciones

Realiza la búsqueda de texto de la frase especificada y proporciona acceso a los resultados de búsqueda a través de la colección [`TextFragments`](../textfragments/).

### Véase también

* clase [TextEditOptions](../../texteditoptions/)
* clase [TextFragmentAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)