---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextAbsorber. Rappresenta un oggetto assorbitore di testo. Esegue l'estrazione del testo e fornisce accesso al risultato tramite l'oggetto [`Text`](./text/).
type: docs
weight: 10800
url: /it/net/aspose.pdf.text/textabsorber/
---
## Classe TextAbsorber

Rappresenta un oggetto assorbitore di testo. Esegue l'estrazione del testo e fornisce accesso al risultato tramite l'oggetto [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Inizializza una nuova istanza di `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Inizializza una nuova istanza di `TextAbsorber` con opzioni di estrazione. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Inizializza una nuova istanza di `TextAbsorber` con opzioni di ricerca del testo. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Inizializza una nuova istanza di `TextAbsorber` con opzioni di estrazione e ricerca del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Elenco di oggetti [`TextExtractionError`](../textextractionerror/). Contiene informazioni sugli errori trovati durante l'estrazione del testo. La ricerca di errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e potrebbe ridurre le prestazioni. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Ottiene o imposta le opzioni di estrazione del testo. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Il valore indica se sono stati trovati errori durante l'estrazione del testo. La ricerca di errori verrà eseguita solo se TextSearchOptions.LogTextExtractionErrors = true; e potrebbe ridurre le prestazioni. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Ottiene il testo estratto che il `TextAbsorber` estrae dal documento o dalla pagina PDF. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Ottiene o imposta le opzioni di ricerca del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Estrae il testo dal documento specificato |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Estrae il testo dalla pagina specificata |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Estrae il testo dal XForm specificato. |

## Osservazioni

L'oggetto `TextAbsorber` viene utilizzato per estrarre testo da un documento Pdf o dalla pagina del documento.

## Esempi

L'esempio dimostra come estrarre testo dalla prima pagina del documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Vedi Anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)