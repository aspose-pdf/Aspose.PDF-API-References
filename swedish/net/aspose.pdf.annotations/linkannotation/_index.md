---
title: LinkAnnotation
second_title: Aspose.PDF för .NET API Referens
description: Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras.
type: docs
weight: 630
url: /sv/net/aspose.pdf.annotations/linkannotation/
---
## LinkAnnotation class

Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras.

```csharp
public sealed class LinkAnnotation : Annotation
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LinkAnnotation](linkannotation)(Page, Rectangle) | Skapar ny länkkommentar på den angivna sidan. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Action](../../aspose.pdf.annotations/linkannotation/action) { get; set; } | En åtgärd som ska utföras när länkkommentaren är aktiverad. |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Hämtar lista över anteckningsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Hämtar eller ställer in aktuellt annoteringsutseendeläge. |
| override [AnnotationType](../../aspose.pdf.annotations/linkannotation/annotationtype) { get; } | Får typ av anteckning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Hämtar utseendeordbok för anteckningen. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Hämtar eller ställer in annoteringsgränsegenskaper.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Får annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [Destination](../../aspose.pdf.annotations/linkannotation/destination) { get; set; } | En destination som ska visas när anteckningen aktiveras. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Får det fullständiga kvalificerade namnet på anteckningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| [Highlighting](../../aspose.pdf.annotations/linkannotation/highlighting) { get; set; } | Den visuella effekten som ska användas när musknappen trycks ned eller hålls nere i dess aktiva område. |
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
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/linkannotation/accept)(AnnotationSelector) | Accepterar besökarobjekt för att bearbeta anteckningen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Uppdatera parametrar och utseende, enligt matristransformationen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klonar denna instans. Virtuell metod. Returnera alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Placerar anteckningsinnehåll direkt på sidan, annotationsobjekt kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returnerar rektangel av anteckning med hänsyn till sidrotation. |

### Se även

* class [Annotation](../annotation)
* namnutrymme [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
