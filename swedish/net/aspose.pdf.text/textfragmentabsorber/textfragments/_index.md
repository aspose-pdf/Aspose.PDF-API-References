---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextFragmentAbsorber-egenskap. Hämtar en samling av sökförekomster som presenteras med TextFragment-objekt"
type: docs
weight: 90
url: /sv/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

Hämtar en samling av sökförekomster som presenteras med [`TextFragment`](../../textfragment/)-objekt.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Exempel

Exemplet visar hur man hittar text på den första PDF-dokumentets sida och ersätter alla sökförekomster med ny text.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Hitta teckensnitt som ska användas för att ändra dokumentets textteckensnitt
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Skapa ett TextFragmentAbsorber‑objekt för att hitta alla förekomster av texten \"hello world\"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(absorber);

// Ändra text för alla sökträffar
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


