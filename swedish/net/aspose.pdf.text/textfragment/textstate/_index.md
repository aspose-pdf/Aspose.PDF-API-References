---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: TextFragment-egenskap. Hämtar eller ställer in textstatus för den text som TextFragment-objektet representerar
type: docs
weight: 150
url: /sv/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState-egenskap

Hämtar eller ställer in textstatus för den text som [`TextFragment`](../) objektet representerar.

```csharp
public TextFragmentState TextState { get; }
```

## Kommentarer

Ger ett sätt att ändra följande egenskaper för texten: Teckensnitt Teckenstorlek Teckensnittsstil Förgrundsfärg Bakgrundsfärg

## Exempel

Exemplet visar hur man ändrar textfärg och teckenstorlek för texten med `TextState`-objektet.

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

### Se Även

* klass [TextFragmentAbsorber](../../textfragmentabsorber/)
* klass [Document](../../../aspose.pdf/document/)
* klass [TextFragmentState](../../textfragmentstate/)
* klass [TextFragment](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)