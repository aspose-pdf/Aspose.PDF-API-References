---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Costruttore TextFragmentAbsorber. Inizializza una nuova istanza di TextFragmentAbsorber che esegue la ricerca di tutti i segmenti di testo del documento o della pagina."
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

Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crea un oggetto TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Fai in modo che l'assorbitore cerchi tutte le occorrenze di testo "hello world"
absorber.Phrase = "hello world";

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il testo della prima occorrenza di testo
absorber.TextFragments[1].Text = "hi world";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Inizializza una nuova istanza di [`TextFragmentAbsorber`](../) con le opzioni di modifica del testo, che esegue la ricerca di tutti i segmenti di testo del documento o della pagina.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare tutti i frammenti di testo nella prima pagina del documento PDF e sostituire il font per essi.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Trova il font Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Imposta il font per tutti i frammenti di testo
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Salva documento
doc.Save(@"D:\Tests\output.pdf");
```

### Vedi anche

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
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
| phrase | String | Frase che la [`TextFragmentAbsorber`](../) ricerca |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il testo e il carattere della prima occorrenza del testo
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Inizializza una nuova istanza della classe [`TextFragmentAbsorber`](../) per l'oggetto classe System.Text.RegularExpressions.Regex specificato.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | Regex | Oggetto classe System.Text.RegularExpressions.Regex che la [`TextFragmentAbsorber`](../) ricerca |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crea un oggetto TextAbsorber per trovare tutte le istanze della regex di input
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// dovremmo trovare la parola "hello" e sostituirla con "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");
```

### Vedi anche

* class [TextFragmentAbsorber](../)
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
| phrase | String | Frase che la [`TextFragmentAbsorber`](../) ricerca |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca. Ad esempio, ricerca con espressione regolare) |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare il testo con espressione regolare nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e terminano con 'o' usando un'espressione regolare.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// dovremmo trovare la parola "hello" e sostituirla con "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
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
| regex | Regex | Oggetto classe System.Text.RegularExpressions.Regex che la [`TextFragmentAbsorber`](../) ricerca |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca.) |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare il testo con espressione regolare nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e terminano con 'o' usando un'espressione regolare.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// dovremmo trovare la parola "hello" e sostituirla con "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");
```

### Vedi anche

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
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
| regexes | Regex[] | Array di oggetti classe System.Text.RegularExpressions.Regex che la [`TextFragmentAbsorber`](../) ricerca. |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca.). |

## Osservazioni

Esegue la ricerca di testo dell'array di frasi specificato e fornisce l'accesso ai risultati della ricerca tramite il dizionario [`RegexResults`](../regexresults/).

## Esempi

L'esempio dimostra come trovare il testo con un array di espressioni regolari nella prima pagina del documento PDF.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e terminano con 'o' usando un'espressione regolare.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Ottieni i risultati di 
var results = absorber.RegexResults;
```

### Vedi anche

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
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
| phrase | String | Frase che la [`TextFragmentAbsorber`](../) ricerca |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo (Consente di attivare alcune funzionalità di ricerca. Ad esempio, ricerca con espressione regolare) |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

## Esempi

L'esempio dimostra come trovare il testo con espressione regolare nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e terminano con 'o' usando un'espressione regolare.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// dovremmo trovare la parola "hello" e sostituirla con "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
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
| phrase | String | Frase che la [`TextFragmentAbsorber`](../) ricerca |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

### Vedi anche

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
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
| regex | Regex | Oggetto classe System.Text.RegularExpressions.Regex che la [`TextFragmentAbsorber`](../) ricerca |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (Consente di attivare alcune funzionalità di modifica). |

## Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](../textfragments/).

### Vedi anche

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


