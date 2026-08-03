---
title: "Klass ImagePlacement"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.ImagePlacement-klass. Representerar egenskaper hos en bild placerad på en PDF-dokumentsida"
type: docs
weight: 6030
url: /sv/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Representerar egenskaperna för en bild placerad på en Pdf-dokumentsida.

```csharp
public sealed class ImagePlacement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Hämtar sammansättningsparametrar för grafikstatus som är aktiv för bilden placerad på sidan. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Hämtar relaterat XImage-resursobjekt. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Aktuell transformationsmatris för denna bild. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operator som används för att visa bilden. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Hämtar sidan som innehåller bilden. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Hämtar rektangeln för bilden. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Hämtar upplösningen för bilden. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Hämtar rotationsvinkeln för Image. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Ta bort bilden från sidan. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Ersätt bilden i samlingen med en annan bild. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Sparar bilden med motsvarande transformationer: skalning, rotation och upplösning. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Sparar bilden med motsvarande transformationer: skalning, rotation och upplösning. |

## Anmärkningar

När en bild placeras på en sida kan den ha andra dimensioner än de fysiska dimensioner som definieras i [`Resources`](../resources/). Objektet `ImagePlacement` är avsett att tillhandahålla sådan information som dimensioner, upplösning och så vidare.

## Exempel

Exemplet visar hur man hittar bilder på den första PDF-dokumentets sida och får bilder som bitmaps med synliga dimensioner.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett ImagePlacementAbsorber‑objekt för att utföra bildplaceringssökning
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Acceptera absorberaren för första sidan
doc.Pages[1].Accept(abs);

// Hämta bilder med synliga dimensioner
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Hämta bild från resurser
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Skapa ny bitmap med faktiska dimensioner
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


