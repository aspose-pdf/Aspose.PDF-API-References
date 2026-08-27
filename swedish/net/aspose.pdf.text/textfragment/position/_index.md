---
title: "TextFragment.Position"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragment egenskap. Hämtar eller anger textposition för text som representeras av TextFragment-objektet"
type: docs
weight: 90
url: /sv/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

Hämtar eller anger textposition för text som representeras av [`TextFragment`](../)-objektet.

```csharp
public Position Position { get; set; }
```

## Exempel

Exemplet visar hur man visar placeringen av en text som representeras av [`TextFragment`](../)-objektet.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Visa text och placeringsinformation för den första textförekomsten
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


