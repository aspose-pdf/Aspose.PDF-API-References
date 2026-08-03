---
title: "Klass RichMediaAnnotation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.RichMediaAnnotation class. Klassen beskriver RichMediaAnnotation som möjliggör inbäddning av video-/ljuddata i PDF-dokument"
type: docs
weight: 2570
url: /sv/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

Klass beskriver RichMediaAnnotation som tillåter inbäddning av video-/ljuddata i PDF-dokument.

```csharp
public class RichMediaAnnotation : Annotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation/)(Page, Rectangle) | Initierar RichMediaAnnotation. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annoteringsåtgärder. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon/) { get; set; } | Händelse som aktiverar programmet. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller anger aktuellt annoteringsutseende. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendedictionary för annoteringen. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller anger egenskaper för annoteringens kant. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller anger annoteringsfärg. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content/) { get; } | Data för Rich Media-innehållet. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller anger annoteringstext. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables/) { get; set; } | Ställer in eller hämtar flash‑variabler som skickas till spelaren. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer/) { get; set; } | Ställer in eller hämtar anpassad flash‑spelare för att spela video-/ljuddata. |
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
| [Type](../../aspose.pdf.annotations/richmediaannotation/type/) { get; set; } | Hämtar eller anger typ av innehåll. Möjliga värden: Audio, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller anger bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept/)(AnnotationSelector) | Accepterar besökare för denna annotation. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata/)(string, Stream) | Lägg till anpassad namngiven data (till exempel som krävs för flash‑skript). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placera annoteringsinnehåll direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotationen. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent/)(string, Stream) | Ange innehållsström. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter/)(Stream) | Ange postern för annotationen. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update/)() | Uppdaterar data med angivna parametrar. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ActivationEvent](../../aspose.pdf.annotations/richmediaannotation.activationevent) | Händelse som aktiverar annotationen. |
| enum [ContentType](../../aspose.pdf.annotations/richmediaannotation.contenttype) | Typ av multimedia. |

### Se även

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


