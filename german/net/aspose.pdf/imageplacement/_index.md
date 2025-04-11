---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacement-Klasse. Stellt die Eigenschaften eines auf die Pdf-Dokumentseite platzierten Bildes dar
type: docs
weight: 5900
url: /de/net/aspose.pdf/imageplacement/
---
## ImagePlacement-Klasse

Stellt die Eigenschaften eines auf die Pdf-Dokumentseite platzierten Bildes dar.

```csharp
public sealed class ImagePlacement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Gibt die Kompositionsparameter des Grafikstatus zurück, der für das auf die Seite platzierte Bild aktiv ist. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Gibt das zugehörige XImage-Ressourcenobjekt zurück. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Aktuelle Transformationsmatrix für dieses Bild. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operator, der zum Anzeigen des Bildes verwendet wird. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Gibt die Seite zurück, die das Bild enthält. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Gibt das Rechteck des Bildes zurück. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Gibt die Auflösung des Bildes zurück. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Gibt den Rotationswinkel des Bildes zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Löscht das Bild von der Seite. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Ersetzt das Bild in der Sammlung durch ein anderes Bild. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Speichert das Bild mit den entsprechenden Transformationen: Skalierung, Rotation und Auflösung. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Speichert das Bild mit den entsprechenden Transformationen: Skalierung, Rotation und Auflösung. |

## Anmerkungen

Wenn ein Bild auf eine Seite platziert wird, kann es andere Abmessungen haben als die physikalischen Abmessungen, die in [`Resources`](../resources/) definiert sind. Das Objekt `ImagePlacement` soll solche Informationen wie Abmessungen, Auflösung usw. bereitstellen.

## Beispiele

Das Beispiel zeigt, wie man Bilder auf der ersten PDF-Dokumentseite findet und Bilder als Bitmaps mit sichtbaren Abmessungen erhält.

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

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)