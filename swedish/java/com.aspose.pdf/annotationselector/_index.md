---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass används för att välja annoteringar med Visitor‑mallidé."
type: docs
weight: 100
url: /sv/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

Denna klass används för att välja annoteringar med Visitor‑mallidé.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | Initierar en ny instans av klassen AnnotationSelector. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | Initierar en ny instans av klassen AnnotationSelector. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSelected](#getSelected--) | Listan med valda objekt. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Väljer {@code bleedMark} om {@link AnnotationSelector} initierades med ett {@link BleedMarkAnnotation}-objekt. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | Välj caret‑annotation om AnnotationSelector initierades med ett CaretAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | Välj cirkel‑annotation om AnnotationSelector initierades med ett CircleAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | Välj ColorBar‑annotation om AnnotationSelector initierades med ett ColorBar‑objekt. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Välj bilaga‑annotation om AnnotationSelector initierades med ett FileAttachmentAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | Välj fritext‑annotation om AnnotationSelector initierades med ett FreeTextAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | Välj bilaga‑annotation om AnnotationSelector initierades med ett FreeTextAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | Välj bläck‑annotation om AnnotationSelector initierades med ett InkAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | Välj linje‑annotation om AnnotationSelector initierades med ett LineAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | Välj länk‑annotation om AnnotationSelector initierades med ett LinkAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | Välj film‑annotation om AnnotationSelector initierades med ett MovieAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Väljer {@code pageInformation} om {@link AnnotationSelector} initierades med ett {@link PageInformationAnnotation}-objekt. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | Välj PDF3D‑annotation om AnnotationSelector initierades med ett PDF3DAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | Välj polygon‑annotation om AnnotationSelector initierades med ett PolygonAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | Välj polylinje‑annotation om AnnotationSelector initierades med ett PolylineAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | Välj popup‑annotation om AnnotationSelector initierades med ett PopupAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | Välj raderings‑annotation om AnnotationSelector initierades med ett RedactAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Väljer {@code registrationMark} om {@link AnnotationSelector} initierades med ett {@link RegistrationMarkAnnotation}-objekt. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | Välj film‑annotation om AnnotationSelector initierades med ett RichMedia‑annotation‑objekt. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | Välj skärm‑annotation om AnnotationSelector initierades med ett ScreenAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | Välj fyrkant‑annotation om AnnotationSelector initierades med ett SquareAnnotation‑objekt. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | Välj krusig annotation om AnnotationSelector initierades med ett SquigglyAnnotation-objekt. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | Välj stämpelannotation om AnnotationSelector initierades med ett StampAnnotation-objekt. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Välj genomstruken annotation om AnnotationSelector initierades med ett StrikeOutAnnotation-objekt. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | Välj textannotation om AnnotationSelector initierades med ett TextAnnotation-objekt. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Väljer {@code trimMark} om {@link AnnotationSelector} initierades med ett {@link TrimMarkAnnotation}-objekt. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | Välj understruken annotation om AnnotationSelector initierades med ett UnderlineAnnotation-objekt. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | Välj vattenstämpelannotation om AnnotationSelector initierades med ett WatermarkAnnotation-objekt. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | Välj widget-annotation om AnnotationSelector initierades med ett WidgetAnnotation-objekt. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

Initierar en ny instans av klassen AnnotationSelector.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
Initierar en ny instans av klassen AnnotationSelector.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

Listan med valda objekt.

**Returns:**
Lista över Annotation-instansier

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Väljer {@code bleedMark} om {@link AnnotationSelector} initierades med ett {@link BleedMarkAnnotation}-objekt.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
Välj caret‑annotation om AnnotationSelector initierades med ett CaretAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
Välj cirkel‑annotation om AnnotationSelector initierades med ett CircleAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
Välj ColorBar‑annotation om AnnotationSelector initierades med ett ColorBar‑objekt.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
Välj bilaga‑annotation om AnnotationSelector initierades med ett FileAttachmentAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
Välj fritext‑annotation om AnnotationSelector initierades med ett FreeTextAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
Välj bilaga‑annotation om AnnotationSelector initierades med ett FreeTextAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
Välj bläck‑annotation om AnnotationSelector initierades med ett InkAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
Välj linje‑annotation om AnnotationSelector initierades med ett LineAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
Välj länk‑annotation om AnnotationSelector initierades med ett LinkAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
Välj film‑annotation om AnnotationSelector initierades med ett MovieAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Väljer {@code pageInformation} om {@link AnnotationSelector} initierades med ett {@link PageInformationAnnotation}-objekt.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
Välj PDF3D‑annotation om AnnotationSelector initierades med ett PDF3DAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
Välj polygon‑annotation om AnnotationSelector initierades med ett PolygonAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
Välj polylinje‑annotation om AnnotationSelector initierades med ett PolylineAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
Välj popup‑annotation om AnnotationSelector initierades med ett PopupAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
Välj raderings‑annotation om AnnotationSelector initierades med ett RedactAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Väljer {@code registrationMark} om {@link AnnotationSelector} initierades med ett {@link RegistrationMarkAnnotation}-objekt.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
Välj film‑annotation om AnnotationSelector initierades med ett RichMedia‑annotation‑objekt.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
Välj skärm‑annotation om AnnotationSelector initierades med ett ScreenAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
Välj fyrkant‑annotation om AnnotationSelector initierades med ett SquareAnnotation‑objekt.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
Välj krusig annotation om AnnotationSelector initierades med ett SquigglyAnnotation-objekt.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
Välj stämpelannotation om AnnotationSelector initierades med ett StampAnnotation-objekt.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
Välj genomstruken annotation om AnnotationSelector initierades med ett StrikeOutAnnotation-objekt.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
Välj textannotation om AnnotationSelector initierades med ett TextAnnotation-objekt.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Väljer {@code trimMark} om {@link AnnotationSelector} initierades med ett {@link TrimMarkAnnotation}-objekt.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
Välj understruken annotation om AnnotationSelector initierades med ett UnderlineAnnotation-objekt.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
Välj vattenstämpelannotation om AnnotationSelector initierades med ett WatermarkAnnotation-objekt.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
Välj widget-annotation om AnnotationSelector initierades med ett WidgetAnnotation-objekt.
