---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacementAbsorber-Klasse. Stellt ein Absorberobjekt von Bildplatzierungsobjekten dar. Führt die Suche nach Bildverwendungen durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`ImagePlacements`](./imageplacements/)
type: docs
weight: 5910
url: /de/net/aspose.pdf/imageplacementabsorber/
---
## Klasse ImagePlacementAbsorber

Stellt ein Absorberobjekt von Bildplatzierungsobjekten dar. Führt die Suche nach Bildverwendungen durch und bietet Zugriff auf die Suchergebnisse über die Sammlung [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Gibt die Sammlung von Bildplatzierungsereignissen zurück, die mit [`ImagePlacement`](../imageplacement/) Objekten dargestellt werden. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Gibt den Lese-Modus für die Sammlung der Parsing-Operationen zurück/setzt ihn. Dies kann gegen Out-of-Memory-Ausnahmen helfen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Führt die Suche im angegebenen Dokument durch. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Führt die Suche auf der angegebenen Seite durch. |

## Anmerkungen

Das `ImagePlacementAbsorber`-Objekt wird im Wesentlichen im Szenario der Bildsuche verwendet. Wenn die Suche abgeschlossen ist, werden die Vorkommen mit [`ImagePlacement`](../imageplacement/) Objekten dargestellt, die die Sammlung [`ImagePlacements`](./imageplacements/) enthält. Das [`ImagePlacement`](../imageplacement/) Objekt bietet Zugriff auf die Eigenschaften der Bildplatzierung: Abmessungen, Auflösung usw. Die positive Bildrotation erfolgt gegen den Uhrzeigersinn, für die Seite im Uhrzeigersinn. Hier müssen wir den Rotationswinkel des Bildes darstellen, daher ziehen wir den Seitenwinkel vom Bildwinkel ab.

## Beispiele

Das Beispiel zeigt, wie man Bilder auf der ersten Seite des PDF-Dokuments findet und die Eigenschaften der Bildplatzierung erhält.

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

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)