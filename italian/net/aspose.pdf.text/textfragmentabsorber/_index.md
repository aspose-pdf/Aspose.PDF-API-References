---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragmentAbsorber. Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca di testo e fornisce accesso ai risultati della ricerca tramite la collezione TextFragments
type: docs
weight: 10950
url: /it/net/aspose.pdf.text/textfragmentabsorber/
---
## Classe TextFragmentAbsorber

Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca di testo e fornisce accesso ai risultati della ricerca tramite la collezione [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Inizializza una nuova istanza di `TextFragmentAbsorber` che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per l'oggetto della classe System.Text.RegularExpressions.Regex specificato. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Inizializza una nuova istanza di `TextFragmentAbsorber` con opzioni di modifica del testo, che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di modifica del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di modifica del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata, le opzioni di ricerca del testo e le opzioni di modifica del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Elenco di oggetti [`TextExtractionError`](../textextractionerror/). Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca di errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e potrebbe ridurre le prestazioni. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Ottiene o imposta le opzioni di estrazione del testo. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca di errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e potrebbe ridurre le prestazioni. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Ottiene o imposta la frase che il `TextFragmentAbsorber` cerca nel documento o nella pagina PDF. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Ottiene un dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e [`TextFragment`](../textfragment/) come valore. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Ottiene il testo estratto che il [`TextAbsorber`](../textabsorber/) estrae nel documento o nella pagina PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Ottiene la collezione delle occorrenze di ricerca presentate con oggetti [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Ottiene o imposta le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con uno più corto/lungo. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca. Le opzioni abilitano la ricerca utilizzando espressioni regolari. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Applica la dimensione del carattere a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nelle pagina(e) sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Applica il carattere a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nelle pagina(e) sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Applica il carattere e la dimensione a tutti i frammenti di testo che sono stati assorbiti. Funziona più velocemente rispetto al ciclo attraverso i frammenti se tutti i frammenti nelle pagina(e) sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Rimuove tutto il testo dal documento. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Rimuove tutto il testo dalla pagina specificata. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Rimuove il testo all'interno del rettangolo specificato dalla pagina specificata. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Pulisce la collezione TextFragments di questo oggetto `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Esegue la ricerca nel documento specificato. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Esegue la ricerca nella pagina specificata. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Esegue la ricerca nell'oggetto modulo specificato. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Estrae il testo nel XForm specificato. |

## Osservazioni

L'oggetto `TextFragmentAbsorber` è fondamentalmente utilizzato nello scenario di ricerca di testo. Quando la ricerca è completata, le occorrenze sono rappresentate da oggetti [`TextFragment`](../textfragment/) che la collezione [`TextFragments`](./textfragments/) contiene. L'oggetto [`TextFragment`](../textfragment/) fornisce accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (carattere, dimensione del carattere, colore, ecc.).

## Esempi

L'esempio dimostra come trovare testo nella prima pagina del documento PDF e sostituire il testo e il suo carattere.

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

* classe [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)