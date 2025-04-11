---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: Proprietà Font. Ottiene o imposta un valore che indica se il font è incorporato. I font basati su IFont verranno automaticamente suddivisi e incorporati
type: docs
weight: 60
url: /it/net/aspose.pdf.text/font/isembedded/
---
## Proprietà Font.IsEmbedded

Ottiene o imposta un valore che indica se il font è incorporato. I font basati su IFont verranno automaticamente suddivisi e incorporati

```csharp
public bool IsEmbedded { get; set; }
```

## Esempi

Il seguente esempio dimostra come trovare un font, marcarlo come incorporato, cercare testo nella pagina del documento e sostituire il font del testo.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi Anche

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [FontRepository](../../fontrepository/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)