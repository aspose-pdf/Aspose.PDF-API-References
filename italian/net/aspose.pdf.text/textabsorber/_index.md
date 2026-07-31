---
title: "Classe TextAbsorber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextAbsorber. Rappresenta un oggetto assorbitore di testo. Esegue l'estrazione del testo e fornisce l'accesso al risultato tramite l'oggetto Text."
type: docs
weight: 10980
url: /it/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Rappresenta un oggetto assorbitore di testo. Esegue l'estrazione del testo e fornisce l'accesso al risultato tramite l'oggetto [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Inizializza una nuova istanza di `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Inizializza una nuova istanza di `TextAbsorber` con le opzioni di estrazione. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Inizializza una nuova istanza di `TextAbsorber` con le opzioni di ricerca del testo. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Inizializza una nuova istanza di `TextAbsorber` con le opzioni di estrazione e ricerca del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Elenco di oggetti [`TextExtractionError`](../textextractionerror/). Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Ottiene o imposta le opzioni di estrazione del testo. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca degli errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e può ridurre le prestazioni. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Restituisce il testo estratto che `TextAbsorber` estrae dal documento PDF o dalla pagina. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Estrae il testo dal documento specificato |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Estrae il testo dalla pagina specificata |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Estrae il testo sull'XForm specificato. |

## Osservazioni

L'oggetto `TextAbsorber` è usato per estrarre testo da un documento Pdf o dalla pagina del documento.

## Esempi

L'esempio dimostra come estrarre testo nella prima pagina del documento PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre testo
TextAbsorber absorber = new TextAbsorber();

// accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// ottieni il testo estratto
string extractedText = absorber.Text;

```

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


