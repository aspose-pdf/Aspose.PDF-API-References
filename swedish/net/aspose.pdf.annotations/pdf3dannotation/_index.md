---
title: PDF3DAnnotation
second_title: Aspose.PDF för .NET API Referens
description: Klass PDF3DAnnotering. Denna klass kan inte ärvas.
type: docs
weight: 770
url: /sv/net/aspose.pdf.annotations/pdf3dannotation/
---
## PDF3DAnnotation class

Klass PDF3DAnnotering. Denna klass kan inte ärvas.

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PDF3DAnnotation](pdf3dannotation#constructor)(Page, Rectangle, PDF3DArtwork) | Initierar en ny instans av[`PDF3DAnnotation`](../pdf3dannotation) class. |
| [PDF3DAnnotation](pdf3dannotation#constructor_1)(Page, Rectangle, PDF3DArtwork, PDF3DActivation) | Initierar en ny instans av[`PDF3DAnnotation`](../pdf3dannotation) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Hämtar lista över anteckningsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Hämtar eller ställer in aktuellt annoteringsutseendeläge. |
| override [AnnotationType](../../aspose.pdf.annotations/pdf3dannotation/annotationtype) { get; } | Får typ av anteckning. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Hämtar utseendeordbok för anteckningen. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Hämtar eller ställer in annoteringsgränsegenskaper.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Får annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Hämtar eller ställer in annoteringsfärg. |
| [Content](../../aspose.pdf.annotations/pdf3dannotation/content) { get; set; } | Hämtar eller ställer in innehållet. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Hämtar eller ställer in annoteringstext. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Får det fullständiga kvalificerade namnet på anteckningen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Hämtar eller ställer in höjden på annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Hämtar eller ställer in fragmentets hyperlänk (för pdf-generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om detta stycke kommer att finnas i nästa kolumn. Standard är falskt.(för pdf-generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Hämtar eller ställer in ett stycke inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Hämtar eller ställer in ett boolvärde som tvingar fram detta stycke vid ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Hämtar eller ställer in ett boolvärde som indikerar om det aktuella stycket finns kvar på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [LightingScheme](../../aspose.pdf.annotations/pdf3dannotation/lightingscheme) { get; } | Får ljusschemat. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Hämtar eller ställer in en yttre marginal för stycke (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Hämtar eller ställer in datum och tid när anteckningen nyligen ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Hämtar eller ställer in anteckningsnamn på sidan. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Hämtar index över sidan som innehåller anteckningar. |
| [Pdf3DArtwork](../../aspose.pdf.annotations/pdf3dannotation/pdf3dartwork) { get; } | Får 3D-konstverket. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Hämtar eller ställer in anteckningsrektangel. |
| [RenderMode](../../aspose.pdf.annotations/pdf3dannotation/rendermode) { get; } | Hämtar renderingsläget. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Hämtar utseendeordbok för anteckningar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Hämtar eller ställer in textjustering för anteckning. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Hämtar eller ställer in en vertikal justering av stycket |
| [ViewArray](../../aspose.pdf.annotations/pdf3dannotation/viewarray) { get; } | Hämtar vymatrisen. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Hämtar eller ställer in bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Hämtar eller ställer in ett int-värde som anger Z-ordningen för grafen. En graf med större ZIndex kommer att placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. Graf med negativ ZIndex kommer att placeras bakom texten på sidan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pdf3dannotation/accept)(AnnotationSelector) | Accepterar besökare för anteckningsbearbetning. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Uppdatera parametrar och utseende, enligt matristransformationen. |
| [ClearImagePreview](../../aspose.pdf.annotations/pdf3dannotation/clearimagepreview)() | Rensar förhandsgranskningen av bilden. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Klonar denna instans. Virtuell metod. Returnera alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Placerar anteckningsinnehåll direkt på sidan, annotationsobjekt kommer att tas bort. |
| [GetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/getimagepreview)() | Hämtar förhandsgranskningen av bilden. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returnerar rektangel av anteckning med hänsyn till sidrotation. |
| [SetDefaultViewIndex](../../aspose.pdf.annotations/pdf3dannotation/setdefaultviewindex)(int) | Ställer in indexet för standardvyn. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview)(Stream) | Ställer in förhandsvisningen av bilden. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview_1)(string) | Ställer in förhandsvisningen av bilden. |

### Se även

* class [Annotation](../annotation)
* namnutrymme [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
