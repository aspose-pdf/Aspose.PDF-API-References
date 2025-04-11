---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Costruttore di TextFragmentAbsorber. Inizializza una nuova istanza di TextFragmentAbsorber che esegue la ricerca di tutti i segmenti di testo del documento o della pagina
type: docs
weight: 10
url: /it/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Inizializza una nuova istanza di [`TextFragmentAbsorber`](../) che esegue la ricerca di tutti i segmenti di testo del documento o della pagina.

```csharp
public TextFragmentAbsorber()
```

## Osservazioni

Esegue la ricerca di testo e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare testo nella prima pagina del documento PDF e sostituire il testo.

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

### Vedi Anche

* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Inizializza una nuova istanza di [`TextFragmentAbsorber`](../) con opzioni di modifica del testo, che esegue la ricerca di tutti i segmenti di testo del documento o della pagina.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare tutti i frammenti di testo nella prima pagina del documento PDF e sostituire il font per essi.

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

### Vedi Anche

* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per la frase di testo specificata.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il [`TextFragmentAbsorber`](../) cerca |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare testo nella prima pagina del documento PDF e sostituire il testo e il suo font.

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

### Vedi Anche

* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per l'oggetto della classe System.Text.RegularExpressions.Regex specificato.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | Regex | Oggetto della classe System.Text.RegularExpressions.Regex che il [`TextFragmentAbsorber`](../) cerca |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare testo nella prima pagina del documento PDF e sostituire il testo e il suo font.

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

### Vedi Anche

* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per la frase di testo specificata e le opzioni di ricerca del testo.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il [`TextFragmentAbsorber`](../) cerca |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca. Ad esempio, ricerca con espressione regolare) |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare testo con espressione regolare nella prima pagina del documento PDF e sostituire il testo.

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

### Vedi Anche

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per la frase di testo specificata e le opzioni di ricerca del testo.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | Regex | Oggetto della classe System.Text.RegularExpressions.Regex che il [`TextFragmentAbsorber`](../) cerca |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca.) |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare testo con espressione regolare nella prima pagina del documento PDF e sostituire il testo.

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

### Vedi Anche

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per la frase di testo specificata e le opzioni di ricerca del testo.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regexes | Regex[] | Array di oggetti della classe System.Text.RegularExpressions.Regex che il [`TextFragmentAbsorber`](../) cerca. |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca.). |

## Osservazioni

Esegue la ricerca di testo dell'array specificato di frasi e fornisce accesso ai risultati della ricerca tramite il dizionario [`RegexResults`](../regexresults/).

## Esempi

L'esempio dimostra come trovare testo con un array di espressioni regolari nella prima pagina del documento PDF.

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

### Vedi Anche

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per la frase di testo specificata, le opzioni di ricerca del testo e le opzioni di modifica del testo.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il [`TextFragmentAbsorber`](../) cerca |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca. Ad esempio, ricerca con espressione regolare) |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare testo con espressione regolare nella prima pagina del documento PDF e sostituire il testo.

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

### Vedi Anche

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per la frase di testo specificata e le opzioni di modifica del testo.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il [`TextFragmentAbsorber`](../) cerca |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

### Vedi Anche

* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per la frase di testo specificata e le opzioni di modifica del testo.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | Regex | Oggetto della classe System.Text.RegularExpressions.Regex che il [`TextFragmentAbsorber`](../) cerca |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

### Vedi Anche

* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)