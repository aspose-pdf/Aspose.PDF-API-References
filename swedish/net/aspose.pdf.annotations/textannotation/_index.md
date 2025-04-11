---
title: Class TextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.TextAnnotation klass. Representerar en textannotation som är en klisterlapp kopplad till en punkt i PDF-dokumentet
type: docs
weight: 2650
url: /sv/net/aspose.pdf.annotations/textannotation/
---
## TextAnnotation klass

Representerar en textannotation som är en 'klisterlapp' kopplad till en punkt i PDF-dokumentet.

```csharp
public sealed class TextAnnotation : MarkupAnnotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextAnnotation](textannotation/#constructor)(Document) | Konstruktör för annotation när den används i Generator. |
| [TextAnnotation](textannotation/#constructor_1)(Page, Rectangle) | Skapar en ny Text-annotation på den angivna sidan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annotationsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller ställer in aktuell annotationsutseende. |
| override [AnnotationType](../../aspose.pdf.annotations/textannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendediktionären för annotationen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller ställer in annotationens kantkarakteristika. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annotationens egenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller ställer in annotationens färg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller ställer in annotationens text. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Hämtar datum och tid när annotationen skapades. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annotationen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar det fullständigt kvalificerade namnet på annotationen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller ställer in höjden på annotationen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller ställer in fragmenthyperlänken (för pdf-generator). |
| [Icon](../../aspose.pdf.annotations/textannotation/icon/) { get; set; } | Hämtar eller ställer in en ikon som ska användas för att visa annotationen. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | En referens till den annotation som denna annotation är "i svar på". Båda annotationerna måste vara på samma sida i dokumentet. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om detta stycke kommer att vara i nästa kolumn. Standard är falskt. (för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller ställer in om ett stycke är inline. Standard är falskt. (för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller ställer in ett bool-värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt. (för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller ställer in ett bool-värde som indikerar om det aktuella stycket förblir på samma sida som nästa stycke. Standard är falskt. (för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller ställer in en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller ställer in datum och tid när annotationen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller ställer in annotationens namn på sidan. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Hämtar eller ställer in det konstanta opacitetsvärdet som ska användas vid målning av annotationen. |
| [Open](../../aspose.pdf.annotations/textannotation/open/) { get; set; } | Hämtar eller ställer in en flagga som specificerar om annotationen initialt ska visas öppen. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller annotationen. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up-annotation för att ange eller redigera texten som är kopplad till denna annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller ställer in annotationens rektangel. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | En sträng som specificerar relationen (den "svarstyp") mellan denna annotation och en som specificeras av InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Hämtar eller ställer in en rik textsträng som ska visas i pop-up-fönstret när annotationen öppnas. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendediktionären för annotationen. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Hämtar text som representerar beskrivningen av objektet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller ställer in textjustering för annotationen. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Hämtar eller ställer in en text som ska visas i titelraden för annotationen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller ställer in bredden på annotationen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller ställer in ett int-värde som indikerar Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativ. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/textannotation/accept/)(AnnotationSelector) | Accepterar besökarobjekt för att bearbeta annotationen. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textannotation/changeafterresize/)(Matrix) | Åsidosätter definitionen i basklassen med en tom kropp. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Rensar tillstånd och tillståndsmodell för annotationen. Till exempel, rensar granskningsstatus för en annotation. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Återger alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placera annotationens innehåll direkt på sidan, annotationobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annotationen med hänsyn till sidrotation. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Hämtar tillståndet för annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Hämtar tillståndsmodellen för annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Ställer in markerad och omarkerad status för annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Tillståndet ställs in av användaren som skapade den aktuella annotationen. Värdet tas från Title-egenskapen för den aktuella annotationen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Ställer in granskningsstatus för en annotation. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör granskningsstatusmodellen. Observera att tillståndet lagras i andra textannotationer som har tillstånds- och tillståndsmodellnycklar. |

### Se Även

* klass [MarkupAnnotation](../markupannotation/)
* namnrymd [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)