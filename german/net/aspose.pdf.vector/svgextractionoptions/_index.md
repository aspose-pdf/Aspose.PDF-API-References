---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SvgExtractionOptions-Klasse. Stellt eine Optionsklasse zum Extrahieren von Vektorgrafiken aus der PDF-Dokumentseite dar
type: docs
weight: 11240
url: /de/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions-Klasse

Stellt eine Optionsklasse zum Extrahieren von Vektorgrafiken aus der PDF-Dokumentseite dar.

```csharp
public class SvgExtractionOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Ruft die Option ab und legt sie fest, um Unterpfade automatisch in Bilder zu gruppieren. Diese Option schließt die [`GroupStrength`](./groupstrength/) Option aus. |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Ruft die Option ab und legt sie fest, um jeden Unterpfad aus einem PDF-Dokument in separate SVG-Bilder zu extrahieren. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Ruft das Begrenzungsrechteck ab und legt es fest, das den Extraktionsbereich für die SVG-Extraktion definiert. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Ruft eine Option ab und legt sie fest, die die Stärke der Gruppierung von Unterpfaden in Bilder angibt. Ermöglicht die Konfiguration des Grads der Gruppierung von Unterpfaden. Der Wertebereich reicht von 0 bis 1. Ein Wert von 0 entspricht der aktivierten [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) Option. Ein Wert von 1 erstellt ein einzelnes Bild für alle Vektorpfade auf der Seite. Die Option hat einen Effekt, wenn [`AutoGrouping`](./autogrouping/) falsch ist. Der Standardwert ist `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Ruft die minimale Strichbreite ab oder legt sie fest, die im resultierenden SVG verwendet wird. Wenn das PDF eine dünnere Strichbreite verwendet, wird sie durch diese Breite ersetzt. Der Standardwert ist 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Ruft eine Option ab und legt sie fest, um streng zu überprüfen, ob Unterpfade innerhalb des angegebenen Rechtecks in [`ExtractionAreaBound`](./extractionareabound/) liegen. Wenn auf falsch gesetzt, werden Unterpfade, die nicht vollständig in [`ExtractionAreaBound`](./extractionareabound/) enthalten sind, extrahiert. Der Standardwert ist `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Ruft ein Flag ab und legt es fest, das bestimmt, ob XForms, die auf Seiten gefunden werden, entpackt werden sollen oder nicht. XForm-Elemente können in verschiedenen SVG-Dateien enden. Nur XForms, die durch Do-Anweisungen aus dem Seiteninhalt gerendert werden, werden entpackt. Verschachtelte XForms werden nicht entpackt. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Ruft die Option ab und legt sie fest, um nur das XForm zu entpacken, das dem angegebenen Prädikat entspricht. |

### Siehe auch

* Namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../)