---
title: "Class TextFragmentAbsorber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Text.TextFragmentAbsorber class. Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione TextFragments."
type: docs
weight: 11130
url: /it/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Rappresenta un oggetto assorbitore di frammenti di testo. Esegue la ricerca del testo e fornisce l'accesso ai risultati della ricerca tramite la collezione [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Inizializza una nuova istanza di `TextFragmentAbsorber` che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per l'oggetto classe System.Text.RegularExpressions.Regex specificato. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Inizializza una nuova istanza di `TextFragmentAbsorber` con le opzioni di modifica del testo, che esegue la ricerca di tutti i segmenti di testo del documento o della pagina. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di modifica del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di modifica del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata e le opzioni di ricerca del testo. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Inizializza una nuova istanza della classe `TextFragmentAbsorber` per la frase di testo specificata, le opzioni di ricerca del testo e le opzioni di modifica del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Elenco di oggetti [`TextExtractionError`](../textextractionerror/). Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Ottiene o imposta le opzioni di estrazione del testo. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Ottiene o imposta la frase che il `TextFragmentAbsorber` ricerca nel documento PDF o nella pagina. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Ottiene il dizionario delle occorrenze di ricerca presentate con la classe System.Text.RegularExpressions.Regex come chiave e [`TextFragment`](../textfragment/) come valore. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Ottiene il testo estratto che il [`TextAbsorber`](../textabsorber/) estrae dal documento PDF o dalla pagina. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Ottiene o imposta le opzioni di modifica del testo. Le opzioni definiscono un comportamento speciale quando il simbolo richiesto non può essere scritto con il carattere. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Ottiene la collezione delle occorrenze di ricerca presentate con oggetti [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Ottiene o imposta le opzioni di sostituzione del testo. Le opzioni definiscono il comportamento quando il testo del frammento viene sostituito con uno più corto o più lungo. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca. Le opzioni consentono la ricerca usando espressioni regolari. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Applica la dimensione del carattere a tutti i frammenti di testo assorbiti. È più veloce rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Applica il carattere a tutti i frammenti di testo assorbiti. È più veloce rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Applica il carattere e la dimensione a tutti i frammenti di testo assorbiti. È più veloce rispetto al ciclo attraverso i frammenti se tutti i frammenti nella/e pagina/e sono stati assorbiti. Altrimenti funziona in modo simile al ciclo. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Rimuove tutto il testo dal documento. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Rimuove tutto il testo dalla pagina specificata. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Rimuove il testo all'interno del rettangolo specificato dalla pagina specificata. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Cancella la collezione TextFragments di questo oggetto `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Esegue la ricerca sul documento specificato. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Esegue la ricerca sulla pagina specificata. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Esegue la ricerca sull'oggetto form specificato. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Estrae il testo sull'XForm specificato. |

## Osservazioni

L'oggetto `TextFragmentAbsorber` è fondamentalmente usato nello scenario di ricerca del testo. Quando la ricerca è completata le occorrenze sono rappresentate con oggetti [`TextFragment`](../textfragment/) contenuti nella collezione [`TextFragments`](./textfragments/). L'oggetto [`TextFragment`](../textfragment/) fornisce l'accesso al testo dell'occorrenza di ricerca, alle proprietà del testo e consente di modificare il testo e cambiare lo stato del testo (carattere, dimensione del carattere, colore ecc).

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

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


