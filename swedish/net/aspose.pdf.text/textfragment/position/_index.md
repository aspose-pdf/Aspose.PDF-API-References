---
title: Position
second_title: Aspose.PDF för .NET API Referens
description: Hämtar eller ställer in textposition för text representerad medTextFragmentaspose.pdf.text/textfragment objekt.
type: docs
weight: 90
url: /sv/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

Hämtar eller ställer in textposition för text, representerad med[`TextFragment`](../../textfragment) objekt.

```csharp
public Position Position { get; set; }
```

### Exempel

Exemplet visar hur man ser placeringen av en text, representerad av[`TextFragment`](../../textfragment) objekt.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa TextFragmentAbsorber-objekt för att hitta alla "hej världen" textförekomster
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Acceptera absorbenten för första sidan
doc.Pages[1].Accept(absorber);

// Visa text och placeringsinformation för första textförekomst
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### Se även

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* class [Document](../../../aspose.pdf/document)
* class [TextSegment](../../textsegment)
* class [Position](../../position)
* class [TextFragment](../../textfragment)
* namnutrymme [Aspose.Pdf.Text](../../textfragment)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
