---
title: TextFragmentAbsorber
second_title: Aspose.PDF per .NET API Reference
description: Inizializza una nuova istanza diTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber che esegue la ricerca di tutti i segmenti di testo del documento o della pagina.
type: docs
weight: 10
url: /it/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber) che esegue la ricerca di tutti i segmenti di testo del documento o della pagina.

```csharp
public TextFragmentAbsorber()
```

### Osservazioni

Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) collezione.

### Esempi

L'esempio mostra come trovare il testo nella prima pagina del documento PDF e sostituirlo.

```csharp
// dovremmo trovare la parola "ciao" e sostituirla con "Ciao"
Document doc = new Document(@"D:\Tests\input.pdf");

// fa in modo che l'assorbitore cerchi tutte le parole che iniziano con 'h' e finiscono con 'o' usando un'espressione regolare.
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// dovremmo trovare la parola "ciao" e sostituirla con "Ciao"
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Crea oggetto TextFragmentAbsorber
absorber.Phrase = "hello world";

// Apri documento
doc.Pages[1].Accept(absorber);

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
absorber.TextFragments[1].Text = "hi world";

// Crea oggetto TextFragmentAbsorber
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber)con opzioni di modifica del testo, che esegue la ricerca di tutti i segmenti di testo del documento o della pagina.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (consente di attivare alcune funzioni di modifica). |

### Osservazioni

Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) collezione.

### Esempi

L'esempio mostra come trovare tutti i frammenti di testo nella prima pagina del documento PDF e sostituirli con il carattere.

```csharp
// Fai in modo che l'assorbitore cerchi tutte le occorrenze di testo "hello world".
Document doc = new Document(@"D:\Tests\input.pdf");

// Modifica il testo della prima occorrenza del testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Modifica il testo della prima occorrenza del testo
doc.Pages[1].Accept(absorber);

// Crea oggetto TextFragmentAbsorber
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Apri documento
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Crea oggetto TextFragmentAbsorber
doc.Save(@"D:\Tests\output.pdf");
```

### Guarda anche

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber) classe per la frase di testo specificata.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il[`TextFragmentAbsorber`](../../textfragmentabsorber) ricerche |

### Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) raccolta.

### Esempi

L'esempio mostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova carattere Courier
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Imposta il carattere per tutti i frammenti di testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Pages[1].Accept(absorber);

// Apri documento
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber) classe per l'oggetto classe System.Text.RegularExpressions.Regex specificato.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | Regex | Oggetto della classe System.Text.RegularExpressions.Regex che il[`TextFragmentAbsorber`](../../textfragmentabsorber) ricerche |

### Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) raccolta.

### Esempi

L'esempio mostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// Crea un oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello world".
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Modifica il testo e il carattere della prima occorrenza del testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Pages[1].Accept(absorber);

// Apri documento
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Save(@"D:\Tests\output.pdf");
```

### Guarda anche

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber)classe per la frase di testo specificata e le opzioni di ricerca del testo.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il[`TextFragmentAbsorber`](../../textfragmentabsorber) ricerche |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca testo (consente di attivare alcune funzioni di ricerca. Ad esempio, ricerca con espressione regolare) |

### Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) raccolta.

### Esempi

L'esempio mostra come trovare il testo con un'espressione regolare nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Crea un oggetto TextAbsorber per trovare tutte le istanze dell'espressione regolare di input
Document doc = new Document(@"D:\Tests\input.pdf");

// Accetta l'assorbitore per la prima pagina
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// dovremmo trovare la parola "ciao" e sostituirla con "Ciao"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber) classe per la frase di testo specificata e le opzioni di ricerca del testo.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | Regex | Oggetto della classe System.Text.RegularExpressions.Regex che il[`TextFragmentAbsorber`](../../textfragmentabsorber) ricerche |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca di testo (consente di attivare alcune funzioni di ricerca.) |

### Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) raccolta.

### Esempi

L'esempio mostra come trovare il testo con un'espressione regolare nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e finiscono con 'o' usando un'espressione regolare.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// dovremmo trovare la parola "ciao" e sostituirla con "Ciao"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");
```

### Guarda anche

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber) classe per la frase di testo specificata, le opzioni di ricerca del testo e le opzioni di modifica del testo.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il[`TextFragmentAbsorber`](../../textfragmentabsorber) ricerche |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca testo (consente di attivare alcune funzioni di ricerca. Ad esempio, ricerca con espressione regolare) |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (consente di attivare alcune funzioni di modifica). |

### Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) raccolta.

### Esempi

L'esempio mostra come trovare il testo con un'espressione regolare nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber che ricerca tutte le parole che iniziano con 'h' e finiscono con 'o' usando un'espressione regolare.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// dovremmo trovare la parola "ciao" e sostituirla con "Ciao"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber) classe per la frase di testo specificata e le opzioni di modifica del testo.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| phrase | String | Frase che il[`TextFragmentAbsorber`](../../textfragmentabsorber) ricerche |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (consente di attivare alcune funzioni di modifica). |

### Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) raccolta.

### Guarda anche

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Inizializza una nuova istanza di[`TextFragmentAbsorber`](../../textfragmentabsorber) classe per la frase di testo specificata e le opzioni di modifica del testo.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | Regex | Oggetto della classe System.Text.RegularExpressions.Regex che il[`TextFragmentAbsorber`](../../textfragmentabsorber) ricerche |
| textEditOptions | TextEditOptions | Opzioni di modifica del testo (consente di attivare alcune funzioni di modifica). |

### Osservazioni

Esegue la ricerca di testo della frase specificata e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](../textfragments) raccolta.

### Guarda anche

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
