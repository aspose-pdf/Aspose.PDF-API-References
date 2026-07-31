---
title: "Classe Font"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.Font. Rappresenta un oggetto font"
type: docs
weight: 10690
url: /it/net/aspose.pdf.text/font/
---
## Font class

Rappresenta un oggetto font.

```csharp
public sealed class Font
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Restituisce il valore BaseFont dell'oggetto font PDF. È anche noto come nome PostScript del font. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | A volte i font PDF (di solito font cinesi/giapponesi/coreani) possono avere un nome di font specifico. Questo nome è il valore della proprietà del font PDF "BaseFont" e a volte questa proprietà può essere rappresentata in forma esadecimale. Se si legge questo nome direttamente potrebbe apparire in forma non leggibile. Per ottenere una forma leggibile è necessario decodificare il nome del font secondo le regole specifiche per questo font. Questa proprietà restituisce il nome del font decodificato, quindi usala nei casi in cui incontri un [`FontName`](./fontname/) non leggibile. Se la proprietà [`FontName`](./fontname/) ha una forma leggibile, questa proprietà sarà la stessa di [`FontName`](./fontname/), così puoi usarla in tutti i casi in cui devi ottenere il nome del font in forma leggibile. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Restituisce il nome del font dell'oggetto `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Proprietà utili per regolare il comportamento del Font |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Restituisce un'indicazione se il font è presente (installato) nel sistema. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Restituisce o imposta un valore che indica se il font è incorporato. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Restituisce o imposta un valore che indica se il font è un subset. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Lo scopo di questo metodo è restituire la descrizione dell'errore se un tentativo di incorporare il font è fallito. Se non ci sono errori restituisce una stringa vuota. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Misura la stringa. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Salva il font nello stream. Nota che il font viene salvato in formato TTF intermedio destinato ad essere usato solo in una copia convertita del documento originale. Il file del font non è destinato ad essere usato al di fuori del contesto del documento originale. |

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e modificare il font della prima occorrenza trovata.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Crea un font e contrassegnalo per l'incorporamento
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Cambia il font della prima occorrenza di testo
absorber.TextFragments[1].TextState.Font = font;


// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


