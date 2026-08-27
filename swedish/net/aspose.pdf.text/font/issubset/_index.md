---
title: "Font.IsSubset"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Font-egenskap. Hämtar eller anger ett värde som indikerar om teckensnittet är en delmängd. Font baserad på IFont kommer automatiskt att vara en delmängd och inbäddad"
type: docs
weight: 70
url: /sv/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

Hämtar eller anger ett värde som indikerar om teckensnittet är en delmängd. Teckensnitt baserade på IFont kommer automatiskt att bli delmängd och inbäddade.

```csharp
public bool IsSubset { get; set; }
```

## Exempel

Exemplet visar hur man söker text på den första sidan och får värdet som indikerar om teckensnittet är en delmängd.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Visa teckensnittets IsSubset‑värde för den första textförekomsten
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


