---
title: Class ScreenAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ScreenAnnotation klass. En skärmanmärkning som specificerar ett område på en sida där medieklipp kan spelas.
type: docs
weight: 2510
url: /sv/net/aspose.pdf.annotations/screenannotation/
---
## ScreenAnnotation klass

En skärmanmärkning som specificerar ett område på en sida där medieklipp kan spelas.

```csharp
public sealed class ScreenAnnotation : Annotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ScreenAnnotation](screenannotation/)(Page, Rectangle, string) | Skapar en ny skärmanmärkning på den angivna sidan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Action](../../aspose.pdf.annotations/screenannotation/action/) { get; } | Hämtar eller ställer in en åtgärd som ska utföras när anmärkningen aktiveras. |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över anmärkningens åtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in det aktuella utseendet för anmärkningen. |
| override [AnnotationType](../../aspose.pdf.annotations/screenannotation/annotationtype/) { get; } | Hämtar typ av anmärkning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendets ordbok för anmärkningen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in anmärkningens kantkarakteristika. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar anmärkningens egenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in anmärkningens färg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in anmärkningens text. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för anmärkningen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet på anmärkningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på anmärkningen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när anmärkningen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in anmärkningens namn på sidan. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller anmärkningen. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller ställer in anmärkningens rektangel. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendets ordbok för anmärkningen. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjusteringen för anmärkningen. |
| [Title](../../aspose.pdf.annotations/screenannotation/title/) { get; set; } | Hämtar eller ställer in titeln för skärmanmärkningen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på anmärkningen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/screenannotation/accept/)(AnnotationSelector) | Accepterar besökarobjekt för att bearbeta anmärkningen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placerar anmärkningens innehåll direkt på sidan, anmärkningens objekt kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Återger rektangeln för anmärkningen med hänsyn till sidrotation. |

### Se Även

* klass [Annotation](../annotation/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* sammansättning [Aspose.PDF](../../)