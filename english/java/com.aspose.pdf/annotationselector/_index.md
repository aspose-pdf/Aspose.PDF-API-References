---
title: AnnotationSelector
linktitle: AnnotationSelector
second_title: Aspose.PDF for Java API Reference
description: This class is used for selecting annotations using Visitor template idea.
type: docs
weight: 100
url: /java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

This class is used for selecting annotations using Visitor template idea.

## Constructors

| Constructor | Description |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | Initializes new instance of the AnnotationSelector class. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | Initializes new instance of the AnnotationSelector class. |

## Methods

| Method | Description |
| --- | --- |
| [getSelected](#getSelected--) | The list of selected objects. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Selects the {@code bleedMark} if the {@link AnnotationSelector} was initialized with a {@link BleedMarkAnnotation} object. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | Select caret annotation if AnnotationSelector was initialized with CaretAnnotation object. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | Select circle annotation if AnnotationSelector was initialized with CircleAnnotation object. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | Select ColorBar annotation if AnnotationSelector was initialized with ColorBar object. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Select attachment annotation if AnnotationSelector was initialized with FileAttachmentAnnotation object. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | Select freetext annotation if AnnotationSelector was initialized with FreeTextAnnotation object. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | Select attachment annotation if AnnotationSelector was initialized with FreeTextAnnotation object. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | Select ink annotation if AnnotationSelector was initialized with InkAnnotation object. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | Select line annotation if AnnotationSelector was initialized with LineAnnotation object. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | Select link annotation if AnnotationSelector was initialized with LinkAnnotation object. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | Select movie annotation if AnnotationSelector was initialized with MovieAnnotation object. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Selects the {@code pageInformation} if the {@link AnnotationSelector} was initialized with a {@link PageInformationAnnotation} object. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | Select PDF3D annotation if AnnotationSelector was initialized with PDF3DAnnotation object. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | Select polygon annotation if AnnotationSelector was initialized with PolygonAnnotation object. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | Select polyline annotation if AnnotationSelector was initialized with PolylineAnnotation object. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | Select popup annotation if AnnotationSelector was initialized with PopupAnnotation object. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | Select redact annotation if AnnotationSelector was initialized with RedactAnnotation object. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Selects the {@code registrationMark} if the {@link AnnotationSelector} was initialized with a {@link RegistrationMarkAnnotation} object. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | Select movie annotation if AnnotationSelector was initialized with RichMedia annotation object. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | Select screen annotation if AnnotationSelector was initialized with ScreenAnnotation object. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | Select square annotation if AnnotationSelector was initialized with SquareAnnotation object. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | Select squiggly annotation if AnnotationSelector was initialized with SquigglyAnnotation object. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | Select stamp annotation if AnnotationSelector was initialized with StampAnnotation object. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Select strikeOut annotation if AnnotationSelector was initialized with StrikeOutAnnotation object. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | Select text annotation if AnnotationSelector was initialized with TextAnnotation object. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Selects the {@code trimMark} if the {@link AnnotationSelector} was initialized with a {@link TrimMarkAnnotation} object. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | Select underline annotation if AnnotationSelector was initialized with UnderlineAnnotation object. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | Select watermark annotation if AnnotationSelector was initialized with WatermarkAnnotation object. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | Select widget annotation if AnnotationSelector was initialized with WidgetAnnotation object. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

Initializes new instance of the AnnotationSelector class.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
Initializes new instance of the AnnotationSelector class.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

The list of selected objects.

**Returns:**
List of Annotation instances

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Selects the {@code bleedMark} if the {@link AnnotationSelector} was initialized with a {@link BleedMarkAnnotation} object.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
Select caret annotation if AnnotationSelector was initialized with CaretAnnotation object.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
Select circle annotation if AnnotationSelector was initialized with CircleAnnotation object.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
Select ColorBar annotation if AnnotationSelector was initialized with ColorBar object.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
Select attachment annotation if AnnotationSelector was initialized with FileAttachmentAnnotation object.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
Select freetext annotation if AnnotationSelector was initialized with FreeTextAnnotation object.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
Select attachment annotation if AnnotationSelector was initialized with FreeTextAnnotation object.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
Select ink annotation if AnnotationSelector was initialized with InkAnnotation object.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
Select line annotation if AnnotationSelector was initialized with LineAnnotation object.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
Select link annotation if AnnotationSelector was initialized with LinkAnnotation object.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
Select movie annotation if AnnotationSelector was initialized with MovieAnnotation object.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Selects the {@code pageInformation} if the {@link AnnotationSelector} was initialized with a {@link PageInformationAnnotation} object.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
Select PDF3D annotation if AnnotationSelector was initialized with PDF3DAnnotation object.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
Select polygon annotation if AnnotationSelector was initialized with PolygonAnnotation object.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
Select polyline annotation if AnnotationSelector was initialized with PolylineAnnotation object.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
Select popup annotation if AnnotationSelector was initialized with PopupAnnotation object.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
Select redact annotation if AnnotationSelector was initialized with RedactAnnotation object.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Selects the {@code registrationMark} if the {@link AnnotationSelector} was initialized with a {@link RegistrationMarkAnnotation} object.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
Select movie annotation if AnnotationSelector was initialized with RichMedia annotation object.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
Select screen annotation if AnnotationSelector was initialized with ScreenAnnotation object.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
Select square annotation if AnnotationSelector was initialized with SquareAnnotation object.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
Select squiggly annotation if AnnotationSelector was initialized with SquigglyAnnotation object.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
Select stamp annotation if AnnotationSelector was initialized with StampAnnotation object.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
Select strikeOut annotation if AnnotationSelector was initialized with StrikeOutAnnotation object.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
Select text annotation if AnnotationSelector was initialized with TextAnnotation object.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Selects the {@code trimMark} if the {@link AnnotationSelector} was initialized with a {@link TrimMarkAnnotation} object.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
Select underline annotation if AnnotationSelector was initialized with UnderlineAnnotation object.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
Select watermark annotation if AnnotationSelector was initialized with WatermarkAnnotation object.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
Select widget annotation if AnnotationSelector was initialized with WidgetAnnotation object.
