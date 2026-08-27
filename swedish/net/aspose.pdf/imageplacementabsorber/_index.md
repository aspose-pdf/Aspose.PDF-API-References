---
title: "Klass ImagePlacementAbsorber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.ImagePlacementAbsorber-klass. Representerar ett absorberande objekt för bildplaceringsobjekt. Utför sökning efter bildanvändningar och ger åtkomst till sökresultaten via ImagePlacements‑samlingen"
type: docs
weight: 6040
url: /sv/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

Representerar ett absorberande objekt för bildplaceringsobjekt. Utför sökning efter bildanvändningar och ger åtkomst till sökresultaten via [`ImagePlacements`](./imageplacements/)‑samlingen.

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
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Hämtar samling av bildplaceringsförekomster som presenteras med [`ImagePlacement`](../imageplacement/)‑objekt. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Hämtar/anger skrivskyddat läge för samling av parsningsoperationer. Det kan hjälpa mot minnesbrist‑undantag. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Utför sökning i det angivna dokumentet. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Utför sökning på den angivna sidan. |

## Anmärkningar

`ImagePlacementAbsorber`‑objektet används i huvudsak i bildsökningsscenario. När sökningen är slutförd representeras förekomsterna med [`ImagePlacement`](../imageplacement/)‑objekt som finns i [`ImagePlacements`](./imageplacements/)‑samlingen. [`ImagePlacement`](../imageplacement/)‑objektet ger åtkomst till bildplaceringsegenskaperna: dimensioner, upplösning osv. Bildens positiva rotation är moturs, för sidan är den medurs. Här måste vi representera bildens rotationsvinkel, så vi drar av sidans vinkel från bildens vinkel.

## Exempel

Exemplet visar hur man hittar bilder på den första PDF-dokumentets sida och får bildplaceringsegenskaperna.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett ImagePlacementAbsorber‑objekt för att utföra bildplaceringssökning
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(abs);

// Visa bildplaceringsegenskaper för alla placeringar
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

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


