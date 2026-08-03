---
title: "TextFragment.TextState"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragment egenskap. Hämtar eller anger texttillstånd för den text som TextFragment-objektet representerar"
type: docs
weight: 150
url: /sv/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

Hämtar eller anger texttillstånd för den text som [`TextFragment`](../)-objektet representerar.

```csharp
public TextFragmentState TextState { get; }
```

## Anmärkningar

Tillhandahåller ett sätt att ändra följande egenskaper för texten: Font FontSize FontStyle ForegroundColor BackgroundColor

## Exempel

Exemplet visar hur man ändrar textfärg och teckenstorlek för texten med `TextState`-objektet.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra förgrundsfärg för den första textförekomsten
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Ändra teckenstorlek för den första textförekomsten
absorber.TextFragments[1].TextState.FontSize = 15;

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


