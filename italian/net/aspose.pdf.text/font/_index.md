---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.Font. Rappresenta l'oggetto font
type: docs
weight: 10510
url: /it/net/aspose.pdf.text/font/
---
## Classe Font

Rappresenta l'oggetto font.

```csharp
public sealed class Font
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Ottiene il valore BaseFont dell'oggetto font PDF. Conosciuto anche come nome PostScript del font. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | A volte i font PDF (di solito font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà "BaseFont" del font PDF e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge questo nome direttamente, potrebbe essere rappresentato in forma non leggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo regole specifiche per questo font. Questa proprietà restituisce il nome del font decodificato, quindi utilizzala per i casi in cui ti imbatti in un [`FontName`](./fontname/) non leggibile. Se la proprietà [`FontName`](./fontname/) ha una forma leggibile, questa proprietà sarà la stessa di [`FontName`](./fontname/), quindi puoi utilizzare questa proprietà per qualsiasi caso in cui hai bisogno di ottenere il nome del font in una forma leggibile. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Ottiene il nome del font dell'oggetto `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Proprietà utili per regolare il comportamento del Font |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Ottiene l'indicazione se il font è presente (installato) nel sistema. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Ottiene o imposta un valore che indica se il font è incorporato. I font basati su IFont saranno automaticamente subset e incorporati |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Ottiene o imposta un valore che indica se il font è un subset. I font basati su IFont saranno automaticamente subset e incorporati |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | L'obiettivo di questo metodo è restituire la descrizione dell'errore se un tentativo di incorporare il font è fallito. Se non ci sono casi di errore, restituisce una stringa vuota. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Misura la stringa. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Salva il font nello stream. Nota che il font è salvato in un formato TTF intermedio destinato ad essere utilizzato solo in una copia convertita del documento originale. Il file del font non è destinato ad essere utilizzato al di fuori del contesto del documento originale. |

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e cambiare il font della prima occorrenza di ricerca.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi Anche

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [FontRepository](../fontrepository/)
* classe [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)