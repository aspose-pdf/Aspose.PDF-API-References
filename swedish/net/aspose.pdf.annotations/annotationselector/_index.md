---
title: "Klass AnnotationSelector"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.AnnotationSelector-klass. Denna klass används för att välja annotationer med hjälp av Visitor-mallidén"
type: docs
weight: 1540
url: /sv/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class

Denna klass används för att välja annotationer med hjälp av Visitor‑mallidén.

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
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | Välj caret-annotation om AnnotationSelector initierades med ett CaretAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | Välj cirkelannotation om AnnotationSelector initierades med ett CircleAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | Välj ColorBar-annotation om AnnotationSelector initierades med ett ColorBar-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | Välj bilaganotering om AnnotationSelector initierades med ett FileAttachmentAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | Välj fritekstannotation om AnnotationSelector initierades med ett FreeTextAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | Välj bilaganotering om AnnotationSelector initierades med ett FreeTextAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | Välj bläckannotation om AnnotationSelector initierades med ett InkAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | Välj linjeannotation om AnnotationSelector initierades med ett LineAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | Välj länkanmärkning om AnnotationSelector initierades med LinkAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | Välj filmanmärkning om AnnotationSelector initierades med MovieAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | Väljer *pageInformation* om `AnnotationSelector` initierades med ett [`PageInformationAnnotation`](../pageinformationannotation/) objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | Välj PDF3D‑anmärkning om AnnotationSelector initierades med PDF3DAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | Välj polygonanmärkning om AnnotationSelector initierades med PolygonAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | Välj polylinje‑anmärkning om AnnotationSelector initierades med PolylineAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | Välj popup‑anmärkning om AnnotationSelector initierades med PopupAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | Välj raderingsanmärkning om AnnotationSelector initierades med RedactAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | Väljer *registrationMark* om `AnnotationSelector` initierades med ett [`RegistrationMarkAnnotation`](../registrationmarkannotation/) objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | Välj filmanmärkning om AnnotationSelector initierades med RichMedia-annotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | Välj skärm‑anmärkning om AnnotationSelector initierades med ScreenAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | Välj fyrkantig anmärkning om AnnotationSelector initierades med SquareAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | Välj krusig anmärkning om AnnotationSelector initierades med SquigglyAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | Välj stämpel‑anmärkning om AnnotationSelector initierades med StampAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | Välj genomstruken anmärkning om AnnotationSelector initierades med StrikeOutAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | Välj text‑anmärkning om AnnotationSelector initierades med TextAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | Väljer *trimMark* om `AnnotationSelector` initierades med ett [`TrimMarkAnnotation`](../trimmarkannotation/) objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | Välj understruken anmärkning om AnnotationSelector initierades med UnderlineAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | Välj vattenstämpel‑anmärkning om AnnotationSelector initierades med WatermarkAnnotation-objekt. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | Välj widget‑anmärkning om AnnotationSelector initierades med WidgetAnnotation-objekt. |

### Se även

* interface [IAnnotationVisitor](../iannotationvisitor/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


