---
title: RedactionAnnotation
second_title: Aspose.PDF för .NET API Referens
description: Representerar Redact-anteckning.
type: docs
weight: 960
url: /sv/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

Representerar Redact-anteckning.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RedactionAnnotation](redactionannotation#constructor)(Document) | Konstruktör för RedactionAnnotation. För användning i Generator. |
| [RedactionAnnotation](redactionannotation#constructor_1)(Page, Rectangle) | Konstruktör för RedactAnnotation. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Hämtar lista över anteckningsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Hämtar eller ställer in aktuellt annoteringsutseendeläge. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype) { get; } | Får typ av anteckning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Hämtar utseendeordbok för anteckningen. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Hämtar eller ställer in annoteringsgränsegenskaper.[`Border`](../annotation/border) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor) { get; set; } | Hämtar eller ställer in färg på kant som ritas när redigering inte är aktiv. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Får annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Hämtar datum och tid när anteckningen skapades. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance) { get; set; } | Hämtar eller ställer in standardutseendesträngen som ska användas vid formatering av texten. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor) { get; set; } | Hämtar eller ställer in färg för fyllningskommentaren. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Får det fullständiga kvalificerade namnet på anteckningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | En referens till anteckningen som denna anteckning är "som svar på". Båda anteckningarna måste finnas på samma sida i dokumentet. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Hämtar eller ställer in datum och tid när anteckningen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Hämtar eller ställer in anteckningsnamn på sidan. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Hämtar eller ställer in det konstanta opacitetsvärdet som ska användas för att måla annoteringen. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext) { get; set; } | Text att skriva ut på redact annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Hämtar index över sidan som innehåller anteckningar. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Popup-kommentar för att skriva in eller redigera texten som är kopplad till denna anteckning. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint) { get; set; } | En matris med 8xN nummer som anger koordinaterna för innehållsregionen som är avsedd att tas bort. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Hämtar eller ställer in anteckningsrektangel. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat) { get; set; } | Om sann överläggstext kommer att upprepas på anteckningen. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | En sträng som anger förhållandet ("svarstypen") mellan denna annotation och en som anges av InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Hämtar eller ställer in en rik textsträng som ska visas i popup-fönstret när anteckningen öppnas. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Hämtar utseendeordbok för anteckningar. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Hämtar text som representerar en beskrivning av objektet. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment) { get; set; } | Hämtar eller sätter. Justering av överläggstext. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Hämtar eller ställer in textjustering för anteckning. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Hämtar eller ställer in en text som ska visas i anteckningens namnlist. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept)(AnnotationSelector) | Accepterar besökarobjekt för att bearbeta anteckningen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Uppdatera parametrar och utseende, enligt matristransformationen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klonar denna instans. Virtuell metod. Returnera alltid null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten)() | Plattar annotering, dvs tar bort annotering och lägger till dess |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returnerar rektangel av anteckning med hänsyn till sidrotation. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact)() | Plattar ut annotering och redigerar sidinnehåll (dvs. tar bort text och bild under redigerad anteckning) |

### Se även

* class [MarkupAnnotation](../markupannotation)
* namnutrymme [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
