---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FreeTextAnnotation klass. Representerar en fri textannotation som visar text direkt på sidan. Till skillnad från en vanlig textannotation har en fri textannotation inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig.
type: docs
weight: 1810
url: /sv/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation klass

Representerar en fri textannotation som visar text direkt på sidan. Till skillnad från en vanlig textannotation har en fri textannotation inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Konstruktör att använda med Generator. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Skapar en ny FreeText-annotation på den angivna sidan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annotationsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in det aktuella annotationens utseendets tillstånd. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för annotationen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annotationens kantkarakteristika. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Array av punkter som specificerar callout-linjen. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annotationens egenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annotationens färg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annotationens text. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Hämtar datum och tid när annotationen skapades. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Hämtar eller ställer in standardutseendesträngen som ska användas för att formatera texten. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Objekt som representerar standardutseendet för FreeText-annotation. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Hämtar eller ställer in en standardstilsträng. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Hämtar eller ställer in linjeavslutningsstilen för linjeavslutningspunkten. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annotationen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet på annotationen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på annotationen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänken (för pdf-generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | En referens till den annotation som denna annotation är "i svar på". Båda annotationerna måste vara på samma sida i dokumentet. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Hämtar eller ställer in avsikten med den fria textannotation. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in ett stycke som är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Hämtar eller ställer in en kod som specificerar formen av kvadrering (justering) som ska användas för att visa annotationens text. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annotationen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annotationens namn på sidan. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Hämtar eller ställer in det konstanta opacitetsvärdet som ska användas vid målning av annotationen. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller annotationen. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Popup-annotation för att ange eller redigera texten som är kopplad till denna annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller ställer in annotationens rektangel. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | En sträng som specificerar relationen (den "svarstyp") mellan denna annotation och en som specificeras av InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Hämtar eller ställer in en rik textsträng som ska visas i popup-fönstret när annotationen öppnas. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Vinkel för annotationens rotation. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Hämtar eller ställer in linjeavslutningsstilen för linjeavslutningspunkten. Denna egenskap är föråldrad, vänligen använd EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för annotationen. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Hämtar text som representerar beskrivningen av objektet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjusteringen för annotationen. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | Rektangel som beskriver de numeriska skillnaderna mellan två rektanglar: Rect-posten för annotationen och en rektangel som finns inom den rektangeln. Den inre rektangeln är där annotationens text ska visas. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Hämtar eller ställer in stilen för texten i utseendet. När textstilen ändras uppdateras textens utseende. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Hämtar eller ställer in en text som ska visas i titelraden för annotationen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annotationen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Accepterar besöksobjekt för att bearbeta annotationen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Rensar tillstånd och tillståndsmodell för annotationen. Till exempel, rensar granskningsstatus för en annotation. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placerar annotationens innehåll direkt på sidan, annotationens objekt kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Återger rektangeln för annotationen med hänsyn till sidrotation. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Hämtar tillståndet för annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Hämtar tillståndsmodellen för annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Ställer in markerat och omarkerat tillstånd för annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Tillståndet ställs in av användaren som skapade den aktuella annotationen. Värdet tas från Title-egenskapen för den aktuella annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |

### Se Även

* klass [MarkupAnnotation](../markupannotation/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)