---
title: "Klass ColorBarAnnotation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.ColorBarAnnotation-klass. Klass som representerar ColorBarAnnotation‑annotation. Egenskapen Color ignoreras och ColorsOfCMYK‑färgen används istället. Vid skapandet bestämmer förhållandet mellan bredd och höjd orienteringen av annotationen, horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox och om den inte gör det flyttas den till den närmaste positionen utanför TrimBox med hänsyn till annotationens orientering. Det är möjligt att minska bredden och höjden så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll; i så fall finns annotationen på sidan men visas inte."
type: docs
weight: 1690
url: /sv/net/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class

Klass som representerar ColorBarAnnotation‑annotation. Property Color ignoreras, istället används ColorsOfCMYK‑färgen. Vid skapande bestämmer förhållandet mellan bredd och höjd orienteringen av annotationen – horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox, och om den inte gör det flyttas den till den närmaste platsen utanför TrimBox med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll (i så fall finns annotationen på sidan men visas inte).

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Page, Rectangle, ColorsOfCMYK) | Skapar en ny ColorBar‑annotation på den angivna sidan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annoteringsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller anger aktuellt annoteringsutseende. |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendedictionary för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller anger egenskaper för annoteringens kant. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller anger annoteringsfärg. |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | Hämtar eller anger färg (en av cyan, magenta, gul, svart) som annotationen ritar med. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller anger annoteringstext. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flaggor för annoteringen. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Hämtar fullt kvalificerat namn för annoteringen. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Hämtar eller anger höjd för annoteringen. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Hämtar eller anger fragmentets hyperlänk (för PDF‑generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om detta stycke ska vara i nästa kolumn. Standard är false. (för PDF‑generering) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Hämtar eller anger att ett stycke är inline. Standard är falskt.(för pdf-generering) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Hämtar eller anger ett booleskt värde som tvingar detta stycke att genereras på en ny sida. Standard är falskt.(för pdf-generering) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Hämtar eller anger ett booleskt värde som indikerar om det aktuella stycket förblir på samma sida tillsammans med nästa stycke. Standard är falskt.(för pdf-generering) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Hämtar eller anger en yttre marginal för stycket (för pdf-generering) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Hämtar eller anger datum och tid då annotationen senast ändrades. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Hämtar eller anger annoteringsnamn på sidan. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Hämtar index för sidan som innehåller annoteringen. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller anger annoteringsrektangeln. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendeordbok för annotationen. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller anger textjustering för annotationen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller anger bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | Accepterar besökarobjekt för att bearbeta anteckningen. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | Uppdatera parametrar och utseende enligt matrisomvandlingen och flyttning utanför TrimBox om nödvändigt. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placera annoteringsinnehåll direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotationen. |

### Se även

* class [PrinterMarkAnnotation](../printermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


