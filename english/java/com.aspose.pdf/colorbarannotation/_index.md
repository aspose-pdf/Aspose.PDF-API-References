---
title: ColorBarAnnotation
linktitle: ColorBarAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing ColorBarAnnotation annotation. Property Color ignored, instead used ColorsOfCMYK color. On creation, the ratio of width and height determines the orientation.
type: docs
weight: 680
url: /java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Class representing ColorBarAnnotation annotation. Property Color ignored, instead used ColorsOfCMYK color. On creation, the ratio of width and height determines the orientation of the annotation - horizontal or vertical. Next, it checks that the annotation rectangle is outside the TrimBox, and if not, then it is shifted to the nearest location outside the TrimBox, taking into account the orientation of the annotation. It is possible to reduce the width (height) so that the annotation fits outside the TrimBox. If there is no space for the layout, the width/height can be set to zero (in this case, the annotation is present on the page, but not displayed).

## Constructors

| Constructor | Description |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new ColorBar annotation on the specified page. Default ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Creates new ColorBar annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Update parameters and appearance, according to the matrix transform and moving outside of TrimBox if nesseary. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getColorOfCMYK](#getColorOfCMYK--) | Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Creates new ColorBar annotation on the specified page. Default ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Creates new ColorBar annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Update parameters and appearance, according to the matrix transform and moving outside of TrimBox if nesseary.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
int value

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing.

**Returns:**
ColorsOfCMYK element

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing.
