---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: Proprietà TextFragment. Ottiene o imposta lo stato del testo per il testo che l'oggetto TextFragment rappresenta
type: docs
weight: 150
url: /it/net/aspose.pdf.text/textfragment/textstate/
---
## Proprietà TextFragment.TextState

Ottiene o imposta lo stato del testo per il testo che l'oggetto [`TextFragment`](../) rappresenta.

```csharp
public TextFragmentState TextState { get; }
```

## Osservazioni

Fornisce un modo per cambiare le seguenti proprietà del testo: Font DimensioneFont StileFont ColorePrimoPiano ColoreSfondo

## Esempi

L'esempio dimostra come cambiare il colore del testo e la dimensione del font del testo con l'oggetto `TextState`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi Anche

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextFragmentState](../../textfragmentstate/)
* classe [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)