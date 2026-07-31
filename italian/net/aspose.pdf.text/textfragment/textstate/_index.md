---
title: "TextFragment.TextState"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragment. Ottiene o imposta lo stato del testo per il testo rappresentato dall'oggetto TextFragment"
type: docs
weight: 150
url: /it/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

Ottiene o imposta lo stato del testo per il testo rappresentato dall'oggetto [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## Osservazioni

Fornisce un modo per modificare le seguenti proprietà del testo: Font FontSize FontStyle ForegroundColor BackgroundColor

## Esempi

L'esempio dimostra come modificare il colore del testo e la dimensione del carattere del testo con l'oggetto `TextState`.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il colore di primo piano della prima occorrenza di testo
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Modifica la dimensione del carattere della prima occorrenza di testo
absorber.TextFragments[1].TextState.FontSize = 15;

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


