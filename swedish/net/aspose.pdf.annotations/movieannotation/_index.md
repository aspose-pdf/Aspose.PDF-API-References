---
title: "Klass MovieAnnotation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.MovieAnnotation class. Representerar en filmanteckning som innehåller animerad grafik och ljud som ska visas på datorskärmen och genom högtalarna. När anteckningen aktiveras spelas filmen."
type: docs
weight: 2200
url: /sv/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

Representerar en film‑annotation som innehåller animerad grafik och ljud som ska visas på datorskärmen och genom högtalarna. När annotationen aktiveras spelas filmen upp.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Konstruktor för användning med Generator. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | Skapar en ny Sound-anteckning på den angivna sidan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Hämtar lista över annoteringsåtgärder. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Hämtar eller anger aktuellt annoteringsutseende. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | Hämtar typ av annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Hämtar utseendedictionary för annoteringen. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | Hämtar eller anger bredden och höjden på filmens avgränsningsruta, i pixlar. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Hämtar eller anger egenskaper för annoteringens kant. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Hämtar annoteringsegenskaper. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Hämtar eller anger annoteringsfärg. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Hämtar eller anger annoteringstext. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | Hämtar eller anger en filspecificering som identifierar en självbeskrivande filmfil. |
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
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | Hämtar eller anger en flagga eller ström som specificerar om och hur en postervisningsbild som representerar filmen ska visas. Om true, hämtas postervisningsbilden från filmfilen; om false visas ingen postervisning. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Hämtar eller anger annoteringsrektangeln. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | Hämtar eller anger antalet grader som filmen ska roteras medurs i förhållande till sidan. Värdet ska vara en multipel av 90. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Hämtar utseendeordbok för annotationen. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Hämtar eller anger textjustering för annotationen. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | Hämtar eller anger titeln på filmanteckningen. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering för stycket |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Hämtar eller anger bredden på annoteringen. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Hämtar eller anger ett heltalsvärde som indikerar Z-ordningen för grafen. En graf med större ZIndex placeras över grafen med mindre ZIndex. ZIndex kan vara negativt. En graf med negativ ZIndex placeras bakom texten på sidan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | Accepterar besökarobjekt för att bearbeta anteckningen. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Uppdatera parametrar och utseende enligt matrisomvandlingen. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Klonar denna instans. Virtuell metod. Returnerar alltid null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Placera annoteringsinnehåll direkt på sidan, annoteringsobjektet kommer att tas bort. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returnerar rektangeln för annoteringen med hänsyn till sidrotationen. |

### Se även

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


