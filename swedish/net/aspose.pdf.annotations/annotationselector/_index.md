---
title: Class AnnotationSelector
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationSelector klass. Denna klass används för att välja annotationer med hjälp av Visitor-mallens idé
type: docs
weight: 1450
url: /sv/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector klass

Denna klass används för att välja annotationer med hjälp av Visitor-mallens idé.

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | Initierar en ny instans av AnnotationSelector-klassen. |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | Initierar ett nytt `AnnotationSelector`-objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | Listan över valda objekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | Väljer *bleedMark* om `AnnotationSelector` initierades med ett [`BleedMarkAnnotation`](../bleedmarkannotation/) objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | Väljer markörannotation om AnnotationSelector initierades med ett CaretAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | Väljer cirkelannotation om AnnotationSelector initierades med ett CircleAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | Väljer ColorBar-annotation om AnnotationSelector initierades med ett ColorBar-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | Väljer bilaga-annotation om AnnotationSelector initierades med ett FileAttachmentAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | Väljer fri text-annotation om AnnotationSelector initierades med ett FreeTextAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | Väljer bilaga-annotation om AnnotationSelector initierades med ett FreeTextAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | Väljer bläckannotation om AnnotationSelector initierades med ett InkAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | Väljer linjeannotation om AnnotationSelector initierades med ett LineAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | Väljer länkannotation om AnnotationSelector initierades med ett LinkAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | Väljer filmannotation om AnnotationSelector initierades med ett MovieAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | Väljer *pageInformation* om `AnnotationSelector` initierades med ett [`PageInformationAnnotation`](../pageinformationannotation/) objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | Väljer PDF3D-annotation om AnnotationSelector initierades med ett PDF3DAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | Väljer polygonannotation om AnnotationSelector initierades med ett PolygonAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | Väljer polyline-annotation om AnnotationSelector initierades med ett PolylineAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | Väljer popup-annotation om AnnotationSelector initierades med ett PopupAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | Väljer redigera-annotation om AnnotationSelector initierades med ett RedactAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | Väljer *registrationMark* om `AnnotationSelector` initierades med ett [`RegistrationMarkAnnotation`](../registrationmarkannotation/) objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | Väljer filmannotation om AnnotationSelector initierades med ett RichMedia-annotationsobjekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | Väljer skärmanimation om AnnotationSelector initierades med ett ScreenAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | Väljer fyrkantig annotation om AnnotationSelector initierades med ett SquareAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | Väljer vågig annotation om AnnotationSelector initierades med ett SquigglyAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | Väljer stämpelannotation om AnnotationSelector initierades med ett StampAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | Väljer strykning-annotation om AnnotationSelector initierades med ett StrikeOutAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | Väljer textannotation om AnnotationSelector initierades med ett TextAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | Väljer *trimMark* om `AnnotationSelector` initierades med ett [`TrimMarkAnnotation`](../trimmarkannotation/) objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | Väljer understruken annotation om AnnotationSelector initierades med ett UnderlineAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | Väljer vattenstämpelannotation om AnnotationSelector initierades med ett WatermarkAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | Väljer widgetannotation om AnnotationSelector initierades med ett WidgetAnnotation-objekt. |

### Se Även

* interface [IAnnotationVisitor](../iannotationvisitor/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)