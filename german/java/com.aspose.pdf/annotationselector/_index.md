---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse wird verwendet, um Annotationen mithilfe des Visitor-Template-Konzepts auszuwählen."
type: docs
weight: 100
url: /de/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

Diese Klasse wird verwendet, um Annotationen mithilfe des Visitor-Template-Konzepts auszuwählen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | Initialisiert eine neue Instanz der Klasse AnnotationSelector. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | Initialisiert eine neue Instanz der Klasse AnnotationSelector. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSelected](#getSelected--) | Die Liste der ausgewählten Objekte. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Wählt das {@code bleedMark} aus, wenn der {@link AnnotationSelector} mit einem {@link BleedMarkAnnotation}-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | Wählt die Caret‑Annotation aus, wenn AnnotationSelector mit einem CaretAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | Wählt die Kreis‑Annotation aus, wenn AnnotationSelector mit einem CircleAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | Wählt die ColorBar‑Annotation aus, wenn AnnotationSelector mit einem ColorBar‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Wählt die Anhang‑Annotation aus, wenn AnnotationSelector mit einem FileAttachmentAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | Wählt die Freitext‑Annotation aus, wenn AnnotationSelector mit einem FreeTextAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | Wählt die Anhang‑Annotation aus, wenn AnnotationSelector mit einem FreeTextAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | Wählt die Ink‑Annotation aus, wenn AnnotationSelector mit einem InkAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | Wählt die Linien‑Annotation aus, wenn AnnotationSelector mit einem LineAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | Wählt die Link‑Annotation aus, wenn AnnotationSelector mit einem LinkAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | Wählt die Film‑Annotation aus, wenn AnnotationSelector mit einem MovieAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Wählt die {@code pageInformation} aus, wenn der {@link AnnotationSelector} mit einem {@link PageInformationAnnotation}-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | Wählt die PDF3D‑Annotation aus, wenn AnnotationSelector mit einem PDF3DAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | Wählt die Polygon‑Annotation aus, wenn AnnotationSelector mit einem PolygonAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | Wählt die Polyline‑Annotation aus, wenn AnnotationSelector mit einem PolylineAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | Wählt die Popup‑Annotation aus, wenn AnnotationSelector mit einem PopupAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | Wählt die Redact‑Annotation aus, wenn AnnotationSelector mit einem RedactAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Wählt die {@code registrationMark} aus, wenn der {@link AnnotationSelector} mit einem {@link RegistrationMarkAnnotation}-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | Wählt die Film‑Annotation aus, wenn AnnotationSelector mit einem RichMedia‑Annotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | Wählt die Screen‑Annotation aus, wenn AnnotationSelector mit einem ScreenAnnotation‑Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | Wählen Sie die quadratische Annotation aus, wenn AnnotationSelector mit einem SquareAnnotation-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | Wählen Sie die wellige Annotation aus, wenn AnnotationSelector mit einem SquigglyAnnotation-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | Wählen Sie die Stempel-Annotation aus, wenn AnnotationSelector mit einem StampAnnotation-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Wählen Sie die Durchgestrichene Annotation aus, wenn AnnotationSelector mit einem StrikeOutAnnotation-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | Wählen Sie die Text-Annotation aus, wenn AnnotationSelector mit einem TextAnnotation-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Wählt das {@code trimMark} aus, wenn {@link AnnotationSelector} mit einem {@link TrimMarkAnnotation}-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | Wählen Sie die Unterstrichene Annotation aus, wenn AnnotationSelector mit einem UnderlineAnnotation-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | Wählen Sie die Wasserzeichen-Annotation aus, wenn AnnotationSelector mit einem WatermarkAnnotation-Objekt initialisiert wurde. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | Wählen Sie die Widget-Annotation aus, wenn AnnotationSelector mit einem WidgetAnnotation-Objekt initialisiert wurde. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

Initialisiert eine neue Instanz der Klasse AnnotationSelector.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
Initialisiert eine neue Instanz der Klasse AnnotationSelector.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

Die Liste der ausgewählten Objekte.

**Returns:**
Liste der Annotation-Instanzen

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Wählt das {@code bleedMark} aus, wenn der {@link AnnotationSelector} mit einem {@link BleedMarkAnnotation}-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
Wählt die Caret‑Annotation aus, wenn AnnotationSelector mit einem CaretAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
Wählt die Kreis‑Annotation aus, wenn AnnotationSelector mit einem CircleAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
Wählt die ColorBar‑Annotation aus, wenn AnnotationSelector mit einem ColorBar‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
Wählt die Anhang‑Annotation aus, wenn AnnotationSelector mit einem FileAttachmentAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
Wählt die Freitext‑Annotation aus, wenn AnnotationSelector mit einem FreeTextAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
Wählt die Anhang‑Annotation aus, wenn AnnotationSelector mit einem FreeTextAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
Wählt die Ink‑Annotation aus, wenn AnnotationSelector mit einem InkAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
Wählt die Linien‑Annotation aus, wenn AnnotationSelector mit einem LineAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
Wählt die Link‑Annotation aus, wenn AnnotationSelector mit einem LinkAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
Wählt die Film‑Annotation aus, wenn AnnotationSelector mit einem MovieAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Wählt die {@code pageInformation} aus, wenn der {@link AnnotationSelector} mit einem {@link PageInformationAnnotation}-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
Wählt die PDF3D‑Annotation aus, wenn AnnotationSelector mit einem PDF3DAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
Wählt die Polygon‑Annotation aus, wenn AnnotationSelector mit einem PolygonAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
Wählt die Polyline‑Annotation aus, wenn AnnotationSelector mit einem PolylineAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
Wählt die Popup‑Annotation aus, wenn AnnotationSelector mit einem PopupAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
Wählt die Redact‑Annotation aus, wenn AnnotationSelector mit einem RedactAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Wählt die {@code registrationMark} aus, wenn der {@link AnnotationSelector} mit einem {@link RegistrationMarkAnnotation}-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
Wählt die Film‑Annotation aus, wenn AnnotationSelector mit einem RichMedia‑Annotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
Wählt die Screen‑Annotation aus, wenn AnnotationSelector mit einem ScreenAnnotation‑Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
Wählen Sie die quadratische Annotation aus, wenn AnnotationSelector mit einem SquareAnnotation-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
Wählen Sie die wellige Annotation aus, wenn AnnotationSelector mit einem SquigglyAnnotation-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
Wählen Sie die Stempel-Annotation aus, wenn AnnotationSelector mit einem StampAnnotation-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
Wählen Sie die Durchgestrichene Annotation aus, wenn AnnotationSelector mit einem StrikeOutAnnotation-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
Wählen Sie die Text-Annotation aus, wenn AnnotationSelector mit einem TextAnnotation-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Wählt das {@code trimMark} aus, wenn {@link AnnotationSelector} mit einem {@link TrimMarkAnnotation}-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
Wählen Sie die Unterstrichene Annotation aus, wenn AnnotationSelector mit einem UnderlineAnnotation-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
Wählen Sie die Wasserzeichen-Annotation aus, wenn AnnotationSelector mit einem WatermarkAnnotation-Objekt initialisiert wurde.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
Wählen Sie die Widget-Annotation aus, wenn AnnotationSelector mit einem WidgetAnnotation-Objekt initialisiert wurde.
