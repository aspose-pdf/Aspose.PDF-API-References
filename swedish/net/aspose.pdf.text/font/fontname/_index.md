---
title: "Font.FontName"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Font egenskap. Hämtar teckensnittsnamnet för Font-objektet"
type: docs
weight: 30
url: /sv/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

Hämtar teckensnittsnamnet för [`Font`](../)-objektet.

```csharp
public string FontName { get; }
```

## Exempel

Exemplet visar hur man söker text på den första sidan och visar teckensnittsnamnet för den första textförekomsten.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Visa teckensnittsnamnet för den första textförekomsten
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


