---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Construtor do TextFragmentAbsorber. Inicializa uma nova instância do TextFragmentAbsorber que realiza a busca de todos os segmentos de texto do documento ou página
type: docs
weight: 10
url: /pt/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Inicializa uma nova instância do [`TextFragmentAbsorber`](../) que realiza a busca de todos os segmentos de texto do documento ou página.

```csharp
public TextFragmentAbsorber()
```

## Remarks

Realiza a busca de texto e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

## Examples

O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto.

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

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Inicializa uma nova instância do [`TextFragmentAbsorber`](../) com opções de edição de texto, que realiza a busca de todos os segmentos de texto do documento ou página.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opções de edição de texto (Permite ativar alguns recursos de edição). |

## Remarks

Realiza a busca de texto e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

## Examples

O exemplo demonstra como encontrar todos os fragmentos de texto na primeira página do documento PDF e substituir a fonte deles.

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

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para a frase de texto especificada.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Frase que o [`TextFragmentAbsorber`](../) busca |

## Remarks

Realiza a busca de texto da frase especificada e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

## Examples

O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte.

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

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para o objeto da classe System.Text.RegularExpressions.Regex especificado.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | Objeto da classe System.Text.RegularExpressions.Regex que o [`TextFragmentAbsorber`](../) busca |

## Remarks

Realiza a busca de texto da frase especificada e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

## Examples

O exemplo demonstra como encontrar texto na primeira página do documento PDF e substituir o texto e sua fonte.

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

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para a frase de texto especificada e opções de busca de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Frase que o [`TextFragmentAbsorber`](../) busca |
| textSearchOptions | TextSearchOptions | Opções de busca de texto (Permite ativar alguns recursos de busca. Por exemplo, busca com expressão regular) |

## Remarks

Realiza a busca de texto da frase especificada e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

## Examples

O exemplo demonstra como encontrar texto com expressão regular na primeira página do documento PDF e substituir o texto.

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

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para a frase de texto especificada e opções de busca de texto.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | Objeto da classe System.Text.RegularExpressions.Regex que o [`TextFragmentAbsorber`](../) busca |
| textSearchOptions | TextSearchOptions | Opções de busca de texto (Permite ativar alguns recursos de busca.) |

## Remarks

Realiza a busca de texto da frase especificada e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

## Examples

O exemplo demonstra como encontrar texto com expressão regular na primeira página do documento PDF e substituir o texto.

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

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para a frase de texto especificada e opções de busca de texto.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regexes | Regex[] | Array de objetos da classe System.Text.RegularExpressions.Regex que o [`TextFragmentAbsorber`](../) busca. |
| textSearchOptions | TextSearchOptions | Opções de busca de texto (Permite ativar alguns recursos de busca.). |

## Remarks

Realiza a busca de texto do array especificado de frases e fornece acesso aos resultados da busca através do dicionário [`RegexResults`](../regexresults/).

## Examples

O exemplo demonstra como encontrar texto com um array de expressões regulares na primeira página do documento PDF.

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

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para a frase de texto especificada, opções de busca de texto e opções de edição de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Frase que o [`TextFragmentAbsorber`](../) busca |
| textSearchOptions | TextSearchOptions | Opções de busca de texto (Permite ativar alguns recursos de busca. Por exemplo, busca com expressão regular) |
| textEditOptions | TextEditOptions | Opções de edição de texto (Permite ativar alguns recursos de edição). |

## Remarks

Realiza a busca de texto da frase especificada e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

## Examples

O exemplo demonstra como encontrar texto com expressão regular na primeira página do documento PDF e substituir o texto.

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

### See Also

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para a frase de texto especificada e opções de edição de texto.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Frase que o [`TextFragmentAbsorber`](../) busca |
| textEditOptions | TextEditOptions | Opções de edição de texto (Permite ativar alguns recursos de edição). |

## Remarks

Realiza a busca de texto da frase especificada e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Inicializa uma nova instância da classe [`TextFragmentAbsorber`](../) para a frase de texto especificada e opções de edição de texto.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | Objeto da classe System.Text.RegularExpressions.Regex que o [`TextFragmentAbsorber`](../) busca |
| textEditOptions | TextEditOptions | Opções de edição de texto (Permite ativar alguns recursos de edição). |

## Remarks

Realiza a busca de texto da frase especificada e fornece acesso aos resultados da busca através da coleção [`TextFragments`](../textfragments/).

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)