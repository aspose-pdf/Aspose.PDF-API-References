---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacement klass. Representerar egenskaper hos en bild som placeras på en Pdf-dokument sida
type: docs
weight: 5900
url: /sv/net/aspose.pdf/imageplacement/
---
## ImagePlacement klass

Representerar egenskaper hos en bild som placeras på en Pdf-dokument sida.

```csharp
public sealed class ImagePlacement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Hämtar sammansättningsparametrar för grafikstatus aktiv för bilden som placeras på sidan. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Hämtar relaterad XImage-resursobjekt. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Aktuell transformationsmatris för denna bild. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operatör som används för att visa bilden. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Hämtar sidan som innehåller bilden. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Hämtar rektangeln av bilden. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Hämtar upplösningen av bilden. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Hämtar rotationsvinkeln av bilden. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Tar bort bilden från sidan. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Ersätter bilden i samlingen med en annan bild. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Sparar bilden med motsvarande transformationer: skalning, rotation och upplösning. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Sparar bilden med motsvarande transformationer: skalning, rotation och upplösning. |

## Kommentarer

När en bild placeras på en sida kan den ha dimensioner som skiljer sig från de fysiska dimensionerna som definieras i [`Resources`](../resources/). Objektet `ImagePlacement` är avsett att tillhandahålla sådan information som dimensioner, upplösning och så vidare.

## Exempel

Exemplet visar hur man hittar bilder på den första PDF-dokument sidan och får bilder som bitmaps med synliga dimensioner.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Se Även

* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)