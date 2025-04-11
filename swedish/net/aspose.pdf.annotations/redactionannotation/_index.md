---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RedactionAnnotation klass. Representerar Redact-annotering
type: docs
weight: 2400
url: /sv/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation klass

Representerar Redact-annotering.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | Konstruktör för RedactionAnnotation. För användning i Generator. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | Konstruktör för RedactAnnotation. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annoteringsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in aktuell annoteringsutseende tillstånd. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Hämtar typ av annotering. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendeordbok för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annoteringsgränskarakteristika. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Hämtar eller ställer in färg på gränsen som ritas när redaktion inte är aktiv. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringskarakteristika. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Hämtar datum och tid när annoteringen skapades. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Hämtar eller ställer in standardutseende-strängen som ska användas för att formatera texten. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Hämtar eller ställer in färg för att fylla annoteringen. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annoteringen. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | Hämtar eller ställer in teckenstorlek för OverlayText. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar fullständigt kvalificerat namn för annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjd för annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänk (för pdf-generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | En referens till den annotering som denna annotering är "i svar på". Båda annoteringarna måste vara på samma sida i dokumentet. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annoteringen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annoteringsnamn på sidan. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Hämtar eller ställer in det konstanta opacitetsvärdet som ska användas vid målning av annoteringen. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Hämtar eller ställer in text som ska skrivas ut på redaktionsannoteringen. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller annoteringen. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-annotering för att ange eller redigera texten som är kopplad till denna annotering. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | En array av 8xN-nummer som specificerar koordinaterna för innehållsområdet som ska tas bort. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller ställer in annoteringsrektangel. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Om sant kommer overlay-texten att upprepas på annoteringen. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | En sträng som specificerar relationen (den "svarstyp") mellan denna annotering och en som specificeras av InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Hämtar eller ställer in en rik textsträng som ska visas i pop-up-fönstret när annoteringen öppnas. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendeordbok för annoteringen. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Hämtar text som representerar beskrivning av objektet. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Hämtar eller ställer in. Justering av Overlay Text. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjustering för annoteringen. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Hämtar eller ställer in en text som ska visas i titelraden för annoteringen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Accepterar besöksobjekt för att bearbeta annoteringen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdaterar parametrar och utseende, enligt matristransformeringen. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Rensar tillstånd och tillståndsmodell för annoteringen. Till exempel, rensar granskningsstatus för en annotering. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Plattar ut annoteringen dvs. tar bort annoteringen och lägger till dess |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotation. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Hämtar tillståndet för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Hämtar tillståndsmodellen för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Plattar ut annoteringen och redigerar sidinnehållet (dvs. tar bort text och bild under den redigerade annoteringen) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Ställer in markerat och omarkerat tillstånd för annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Tillståndet ställs in av användaren som skapade den aktuella annoteringen. Värdet tas från Title-egenskapen för den aktuella annoteringen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Observera att tillståndet lagras i andra textannoteringar som har tillstånds- och tillståndsmodellnycklar. |

### Se Även

* klass [MarkupAnnotation](../markupannotation/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)