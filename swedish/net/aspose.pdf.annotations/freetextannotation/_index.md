---
title: FreeTextAnnotation
second_title: Aspose.PDF för .NET API Referens
description: Representerar en fritextkommentar som visar text direkt på sidan. Till skillnad från en vanlig textkommentar har en fritextkommentar inget öppet eller stängt tillstånd istället för att visas i ett popup-fönster är texten alltid synlig.
type: docs
weight: 430
url: /sv/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

Representerar en fritextkommentar som visar text direkt på sidan. Till skillnad från en vanlig textkommentar har en fritextkommentar inget öppet eller stängt tillstånd; istället för att visas i ett popup-fönster är texten alltid synlig.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [FreeTextAnnotation](freetextannotation#constructor)(Document, DefaultAppearance) | Konstruktör att använda med Generator. |
| [FreeTextAnnotation](freetextannotation#constructor_1)(Page, Rectangle, DefaultAppearance) | Skapar ny fritextkommentar på den angivna sidan. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Hämtar lista över anteckningsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Hämtar eller ställer in aktuellt annoteringsutseendeläge. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype) { get; } | Får typ av anteckning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Hämtar utseendeordbok för anteckningen. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Hämtar eller ställer in annoteringsgränsegenskaper.[`Border`](../annotation/border) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout) { get; set; } | Matris med punkt som anger bildtextlinje. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Får annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Hämtar datum och tid när anteckningen skapades. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance) { get; set; } | Hämtar eller ställer in standardutseendesträngen som ska användas vid formatering av texten. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject) { get; } | Objekt som representerar standardutseendet för FreeText-kommentarer. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle) { get; set; } | Hämtar eller ställer in en standardstilsträng. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle) { get; set; } | Hämtar eller ställer in linjeslutstil för linjeslutpunkt. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Får det fullständiga kvalificerade namnet på anteckningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | En referens till anteckningen som denna anteckning är "som svar på". Båda anteckningarna måste finnas på samma sida i dokumentet. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent) { get; set; } | Hämtar eller ställer in syftet med fritextkommentaren. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification) { get; set; } | Hämtar eller ställer in en kod som anger formen av quadding (justering) som ska användas för att visa anteckningens text. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Hämtar eller ställer in datum och tid när anteckningen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Hämtar eller ställer in anteckningsnamn på sidan. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Hämtar eller ställer in det konstanta opacitetsvärdet som ska användas för att måla annoteringen. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Hämtar index över sidan som innehåller anteckningar. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Popup-kommentar för att skriva in eller redigera texten som är kopplad till denna anteckning. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Hämtar eller ställer in anteckningsrektangel. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | En sträng som anger förhållandet ("svarstypen") mellan denna annotation och en som anges av InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Hämtar eller ställer in en rik textsträng som ska visas i popup-fönstret när anteckningen öppnas. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate) { get; set; } | Annotationsrotationsvinkel. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle) { get; set; } | Hämtar eller ställer in linjeslutstil för linjeslutpunkt. ODenna egenskap är föråldrad, använd EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Hämtar utseendeordbok för anteckningar. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Hämtar text som representerar en beskrivning av objektet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Hämtar eller ställer in textjustering för anteckning. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle) { get; set; } | Rektangel som beskriver de numeriska skillnaderna mellan två rektanglar: Rect-posten för annotation och en rektangel som finns i den rektangeln. Den inre rektangeln är där anteckningens text ska visas. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle) { get; set; } | Hämtar eller ställer in stilen på texten i utseende. när textstilen ändras uppdateras textens utseende. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Hämtar eller ställer in en text som ska visas i anteckningens namnlist. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept)(AnnotationSelector) | Accepterar besökarobjekt för att bearbeta anteckningen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Uppdatera parametrar och utseende, enligt matristransformationen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klonar denna instans. Virtuell metod. Returnera alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Placerar anteckningsinnehåll direkt på sidan, annotationsobjekt kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returnerar rektangel av anteckning med hänsyn till sidrotation. |

### Se även

* class [MarkupAnnotation](../markupannotation)
* namnutrymme [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
