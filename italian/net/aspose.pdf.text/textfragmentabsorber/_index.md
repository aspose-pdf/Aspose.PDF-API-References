---
title: TextFragmentAbsorber
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca di testo e fornisce laccesso ai risultati della ricerca tramiteTextFragments./textfragmentabsorber/textfragments raccolta.
type: docs
weight: 7110
url: /it/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca di testo e fornisce l'accesso ai risultati della ricerca tramite[`TextFragments`](./textfragments) raccolta.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber) che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber) classe per l'oggetto classe System.Text.RegularExpressions.Regex specificato. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber) classe per la frase di testo specificata. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber)con opzioni di modifica del testo, che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber) classe per la frase di testo specificata e le opzioni di modifica del testo. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber) classe per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber) classe per la frase di testo specificata e le opzioni di modifica del testo. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber)classe per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | Inizializza una nuova istanza di[`TextFragmentAbsorber`](../textfragmentabsorber) classe per la frase di testo specificata, le opzioni di ricerca del testo e le opzioni di modifica del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | Elenco di[`TextExtractionError`](../textextractionerror) oggetti. Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; E potrebbe ridurre le prestazioni. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | Ottiene o imposta le opzioni di estrazione del testo. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; E potrebbe ridurre le prestazioni. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | Ottiene o imposta la frase che il[`TextFragmentAbsorber`](../textfragmentabsorber) ricerche nel documento o nella pagina PDF. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | Ottiene il testo estratto che il[`TextAbsorber`](../textabsorber) estratti nel documento o nella pagina PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con font. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | Ottiene la raccolta di occorrenze di ricerca presentate[`TextFragment`](../textfragment) oggetti. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | Ottiene o imposta le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con più corto/lungo. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | Ottiene o imposta le opzioni di ricerca. Le opzioni abilitano la ricerca usando le espressioni regolari. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | Applica la dimensione del carattere per tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente che scorrere i frammenti se tutti i frammenti sulle pagine sono stati assorbiti. Altrimenti funziona in modo simile con il looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | Applica il carattere a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente che scorrere i frammenti se tutti i frammenti sulle pagine sono stati assorbiti. Altrimenti funziona in modo simile con il looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | Applica carattere e dimensione a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente che scorrere i frammenti se tutti i frammenti sulle pagine sono stati assorbiti. Altrimenti funziona in modo simile con il looping. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | Rimuove tutto il testo dal documento. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | Rimuove tutto il testo dalla pagina specificata. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | Rimuove il testo all'interno del rettangolo specificato dalla pagina specificata. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | Cancella la raccolta TextFragments di questo[`TextFragmentAbsorber`](../textfragmentabsorber) oggetto. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | Esegue la ricerca sul documento specificato. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | Esegue la ricerca sulla pagina specificata. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | Esegue la ricerca sull'oggetto modulo specificato. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | Estrae il testo sull'XForm specificato. |

### Osservazioni

Il[`TextFragmentAbsorber`](../textfragmentabsorber) l'oggetto è fondamentalmente utilizzato nello scenario di ricerca di testo. Quando la ricerca è completata, le occorrenze vengono rappresentate con[`TextFragment`](../textfragment) oggetti che il[`TextFragments`](./textfragments) la raccolta contiene. Il[`TextFragment`](../textfragment) l'oggetto fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (carattere, dimensione del carattere, colore, ecc.).

### Esempi

L'esempio mostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Visualizza le informazioni sul testo e sul posizionamento della prima occorrenza del testo
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Visualizza le informazioni sul testo e sul posizionamento della prima occorrenza del testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Visualizza le informazioni sul testo e sul posizionamento della prima occorrenza del testo
doc.Pages[1].Accept(absorber);

// Apri documento
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [TextAbsorber](../textabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../aspose.pdf.text)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
