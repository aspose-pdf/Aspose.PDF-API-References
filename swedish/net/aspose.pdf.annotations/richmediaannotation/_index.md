---
title: RichMediaAnnotation
second_title: Aspose.PDF för .NET API Referens
description: Klassen beskriver RichMediaAnnotation som tillåter inbäddning av video-/ljuddata i PDF-dokument.
type: docs
weight: 1030
url: /sv/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

Klassen beskriver RichMediaAnnotation som tillåter inbäddning av video-/ljuddata i PDF-dokument.

```csharp
public class RichMediaAnnotation : Annotation
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation)(Page, Rectangle) | Initierar RichMediaAnnotation. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Hämtar lista över anteckningsåtgärder. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon) { get; set; } | Händelse som aktiverar applikation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Hämtar eller ställer in aktuellt annoteringsutseendeläge. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype) { get; } | Får typ av anteckning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Hämtar utseendeordbok för anteckningen. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Hämtar eller ställer in annoteringsgränsegenskaper.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Får annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content) { get; } | Data för multimedieinnehåll. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables) { get; set; } | Ställer in eller hämtar flashvariabler som skickas till spelaren. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer) { get; set; } | Ställer in eller skaffar anpassad flashspelare för att spela upp video/ljuddata. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Får det fullständiga kvalificerade namnet på anteckningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Hämtar eller ställer in datum och tid när anteckningen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Hämtar eller ställer in anteckningsnamn på sidan. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Hämtar index över sidan som innehåller anteckningar. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Hämtar eller ställer in anteckningsrektangel. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Hämtar utseendeordbok för anteckningar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Hämtar eller ställer in textjustering för anteckning. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type) { get; set; } | Hämtar eller ställer in typ av innehåll. Möjliga värden: Audio, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept)(AnnotationSelector) | Accepterar besökare för denna kommentar. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata)(string, Stream) | Lägg till anpassade namngivna data (till exempel krävs för flash-skript). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Uppdatera parametrar och utseende, enligt matristransformationen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klonar denna instans. Virtuell metod. Returnera alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Placerar anteckningsinnehåll direkt på sidan, annotationsobjekt kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returnerar rektangel av anteckning med hänsyn till sidrotation. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent)(string, Stream) | Ställ in innehållsström. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter)(Stream) | Ställ affisch för anteckningen. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update)() | Uppdaterar data med angivna parametrar. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| enum [ActivationEvent](richmediaannotation.activationevent) | Händelse som aktiverar anteckning. |
| enum [ContentType](richmediaannotation.contenttype) | Typ av multimedia. |

### Se även

* class [Annotation](../annotation)
* namnutrymme [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
