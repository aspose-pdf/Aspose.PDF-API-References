---
title: Class FileAttachmentAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FileAttachmentAnnotation klass. Klassen beskriver filbilagaannotering
type: docs
weight: 1710
url: /sv/net/aspose.pdf.annotations/fileattachmentannotation/
---
## FileAttachmentAnnotation klass

Klassen beskriver filbilagaannotering.

```csharp
public sealed class FileAttachmentAnnotation : MarkupAnnotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileAttachmentAnnotation](fileattachmentannotation/)(Page, Rectangle, FileSpecification) | Skapar en ny filbilagaannotering på den angivna sidan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annoteringsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in den aktuella annoteringens utseendestatus. |
| override [AnnotationType](../../aspose.pdf.annotations/fileattachmentannotation/annotationtype/) { get; } | Hämtar typ av annotering. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annoteringens kantkarakteristika. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringens egenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annoteringens färg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annoteringens text. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Hämtar datum och tid när annoteringen skapades. |
| [File](../../aspose.pdf.annotations/fileattachmentannotation/file/) { get; set; } | Specifikationen av filen som är kopplad till denna annotering. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet på annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänken (för pdf-generator). |
| [Icon](../../aspose.pdf.annotations/fileattachmentannotation/icon/) { get; set; } | Hämtar eller ställer in ikonen som ska användas för att visa annoteringen. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | En referens till den annotering som denna annotering är "i svar på". Båda annoteringarna måste vara på samma sida i dokumentet. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annoteringen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annoteringens namn på sidan. |
| [Opacity](../../aspose.pdf.annotations/fileattachmentannotation/opacity/) { get; set; } | Hämtar eller ställer in ikonens opacitet från 0 till 1: 0 - helt transparent, 1 - helt ogenomskinlig. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller annoteringen. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-annotering för att ange eller redigera texten som är kopplad till denna annotering. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller ställer in annoteringens rektangel. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | En sträng som specificerar relationen (den "svarstyp") mellan denna annotering och en som specificeras av InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Hämtar eller ställer in en rik textsträng som ska visas i pop-up-fönstret när annoteringen öppnas. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för annoteringen. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Hämtar text som representerar beskrivningen av objektet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjusteringen för annoteringen. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Hämtar eller ställer in en text som ska visas i titelraden för annoteringen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/fileattachmentannotation/accept/)(AnnotationSelector) | Accepterar besöksobjekt för att bearbeta annoteringen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Rensar tillstånd och tillståndsmodell för annoteringen. Till exempel, rensar granskningsstatus för en annotering. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placera annoteringens innehåll direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Hämtar tillståndet för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Hämtar tillståndsmodellen för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Ställer in markerat och omarkerat tillstånd för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Tillståndet ställs in av användaren som skapade den aktuella annoteringen. Värdet tas från Title-egenskapen för den aktuella annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |

### Se Även

* klass [MarkupAnnotation](../markupannotation/)
* namnrum [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* sammansättning [Aspose.PDF](../../)