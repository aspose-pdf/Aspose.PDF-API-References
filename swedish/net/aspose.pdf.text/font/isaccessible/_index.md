---
title: "Font.IsAccessible"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Font‑egenskap. Hämtar information om huruvida teckensnittet är installerat i systemet"
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

Hämtar indikation på om teckensnittet finns (är installerat) i systemet.

```csharp
public bool IsAccessible { get; }
```

## Anmärkningar

Vissa operationer är inte tillgängliga med teckensnitt som inte kunde hittas i systemet.

## Exempel

Exemplet visar hur man söker text på den första sidan och får värdet som indikerar om teckensnittet är installerat i systemet.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Visa teckensnittets IsSubset‑värde för den första textförekomsten
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


