---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacementAbsorber klass. Representerar ett absorberobjekt av bildplaceringsobjekt. Utför sökning av bildanvändningar och ger åtkomst till sökresultat via ImagePlacements-samlingen
type: docs
weight: 5910
url: /sv/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber klass

Representerar ett absorberobjekt av bildplaceringsobjekt. Utför sökning av bildanvändningar och ger åtkomst till sökresultat via [`ImagePlacements`](./imageplacements/) samlingen.

```csharp
public sealed class ImagePlacementAbsorber
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Hämtar samlingen av bildplaceringsförekomster som presenteras med [`ImagePlacement`](../imageplacement/) objekt. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Hämtar/anger skrivskyddat läge för parsning av operationssamlingen. Det kan hjälpa mot minnesöverskridande undantag. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Utför sökning på det angivna dokumentet. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Utför sökning på den angivna sidan. |

## Kommentarer

`ImagePlacementAbsorber` objektet används i grund och botten i bildsökningsscenarier. När sökningen är slutförd representeras förekomsterna med [`ImagePlacement`](../imageplacement/) objekt som [`ImagePlacements`](./imageplacements/) samlingen innehåller. [`ImagePlacement`](../imageplacement/) objektet ger åtkomst till bildplaceringsegenskaper: dimensioner, upplösning etc. Positiv bildrotation är moturs, för sidan är den medurs. Här behöver vi representera bildens rotationsvinkel, så vi drar sidans vinkel från bildens vinkel.

## Exempel

Exemplet visar hur man hittar bilder på den första PDF-dokumentets sida och får bildplaceringsegenskaperna.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### Se Även

* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)