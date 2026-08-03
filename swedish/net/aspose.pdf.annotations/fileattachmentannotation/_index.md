---
title: "Klass FileAttachmentAnnotation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.FileAttachmentAnnotation class. Klassen beskriver filbilagsanteckning"
type: docs
weight: 1800
url: /sv/net/aspose.pdf.annotations/fileattachmentannotation/
---
## FileAttachmentAnnotation class

Klass som beskriver filbilagsannotation.

```csharp
public sealed class FileAttachmentAnnotation : MarkupAnnotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileAttachmentAnnotation](fileattachmentannotation/)(Page, Rectangle, FileSpecification) | Skapar en ny FileAttachment‑anteckning på den angivna sidan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annoteringsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller anger aktuellt annoteringsutseende. |
| override [AnnotationType](../../aspose.pdf.annotations/fileattachmentannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendedictionary för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller anger egenskaper för annoteringens kant. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller anger annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller anger annoteringstext. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Hämtar datum och tid då annoteringen skapades. |
| [File](../../aspose.pdf.annotations/fileattachmentannotation/file/) { get; set; } | Specifikationen av filen som är associerad med denna anteckning. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar fullt kvalificerat namn för annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller anger höjd för annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [Icon](../../aspose.pdf.annotations/fileattachmentannotation/icon/) { get; set; } | Hämtar eller anger ikonen som ska användas vid visning av anteckningen. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | En referens till den annotering som denna annotering är "i svar på". Båda annoteringarna måste vara på samma sida i dokumentet. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller anger datum och tid då annotationen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller anger annoteringsnamn på sidan. |
| [Opacity](../../aspose.pdf.annotations/fileattachmentannotation/opacity/) { get; set; } | Hämtar eller anger ikonens opacitet från 0 till 1: 0 – helt genomskinlig, 1 – helt ogenomskinlig. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller annoteringen. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Popup-annotering för att ange eller redigera texten som är kopplad till denna annotering. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller anger annoteringsrektangeln. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | En sträng som specificerar förhållandet ("svarstypen") mellan denna annotering och den som anges av InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Hämtar eller anger en rik textsträng som ska visas i popup-fönstret när annoteringen öppnas. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendeordbok för annotationen. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Hämtar text som representerar en beskrivning av objektet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller anger textjustering för annotationen. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Hämtar eller anger en textetikett som ska visas i titelraden på annoteringens popup-fönster när det är öppet och aktivt. Detta fält ska identifiera användaren som lade till annoteringen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller anger bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/fileattachmentannotation/accept/)(AnnotationSelector) | Accepterar ett besökarobjekt för att bearbeta anteckningen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Rensar tillstånd och tillståndsmodell för annoteringen. Till exempel rensar granskningsstatusen för en annotering. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placera annoteringsinnehåll direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotationen. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Hämtar tillståndet för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Hämtar tillståndsmodellen för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Ställer in markerat och omarkerat tillstånd för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Ställer in granskningsstatusen för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av den användare som skapade målannoteringen. Värdet hämtas från Title‑egenskapen för målannoteringen. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Ställer in granskningsstatusen för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |

### Se även

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


