---
title: Class RichMediaAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RichMediaAnnotation klass. Klassen beskriver RichMediaAnnotation som tillåter inbäddning av video/audio data i PDF-dokument
type: docs
weight: 2480
url: /sv/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation klass

Klassen beskriver RichMediaAnnotation som tillåter inbäddning av video/audio data i PDF-dokument.

```csharp
public class RichMediaAnnotation : Annotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation/)(Page, Rectangle) | Initierar RichMediaAnnotation. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annoteringsåtgärder. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon/) { get; set; } | Händelse som aktiverar applikationen. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in det aktuella annoteringsutseendet. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för annotationen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annoteringsgränsegenskaper. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringens egenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annoteringens färg. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content/) { get; } | Data för Rich Media-innehållet. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annoteringens text. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables/) { get; set; } | Ställer in eller hämtar flashvariabler som skickas till spelaren. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer/) { get; set; } | Ställer in eller hämtar en anpassad flash-spelare för att spela video/audio data. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annotationen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet på annotationen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på annotationen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänken (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annotationen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annoteringsnamnet på sidan. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller annotationen. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller ställer in annoteringsrektangeln. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för annotationen. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjusteringen för annotationen. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type/) { get; set; } | Hämtar eller ställer in typen av innehåll. Möjliga värden: Audio, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annotationen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept/)(AnnotationSelector) | Accepterar besökare för denna annotation. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata/)(string, Stream) | Lägger till anpassad namngiven data (till exempel nödvändig för flash-skript). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placerar annoteringsinnehållet direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annotationen med hänsyn till sidrotation. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent/)(string, Stream) | Ställer in innehållsström. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter/)(Stream) | Ställer in affischen för annotationen. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update/)() | Uppdaterar data med angivna parametrar. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ActivationEvent](../../aspose.pdf.annotations/richmediaannotation.activationevent) | Händelse som aktiverar annotationen. |
| enum [ContentType](../../aspose.pdf.annotations/richmediaannotation.contenttype) | Typ av multimedia. |

### Se Även

* klass [Annotation](../annotation/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)