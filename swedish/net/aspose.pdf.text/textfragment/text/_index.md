---
title: "TextFragment.Text"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragment-egenskap. Hämtar eller anger String-textobjekt som TextFragment-objektet representerar"
type: docs
weight: 130
url: /sv/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

Hämtar eller anger String-textobjekt som [`TextFragment`](../)-objektet representerar.

```csharp
public string Text { get; set; }
```

## Exempel

Exemplet visar hur man söker efter en text och ersätter den första förekomsten som representeras av [`TextFragment`](../)-objektet.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra teckensnitt för den första textförekomsten
absorber.TextFragments[1].Text = "hi world";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf"); 
```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


