---
title: ColorBarAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing ColorBarAnnotation annotation.
type: docs
weight: 61
url: /java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.PrinterMarkAnnotation](../../com.aspose.pdf/printermarkannotation)
```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Class representing ColorBarAnnotation annotation. Property Color ignored, instead used ColorsOfCMYK color. On creation, the ratio of width and height determines the orientation of the annotation - horizontal or vertical. Next, it checks that the annotation rectangle is outside the TrimBox, and if not, then it is shifted to the nearest location outside the TrimBox, taking into account the orientation of the annotation. It is possible to reduce the width (height) so that the annotation fits outside the TrimBox. If there is no space for the layout, the width/height can be set to zero (in this case, the annotation is present on the page, but not displayed).
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorBarAnnotation(Page page, Rectangle rect)](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new ColorBar annotation on the specified page. |
| [ColorBarAnnotation(Page page, Rectangle rect, int colorOfCMYK)](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-int-) | Creates new ColorBar annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getColorOfCMYK()](#getColorOfCMYK--) | Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing. |
| [setColorOfCMYK(int value)](#setColorOfCMYK-int-) | Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Update parameters and appearance, according to the matrix transform and moving outside of TrimBox if nesseary. |
### ColorBarAnnotation(Page page, Rectangle rect) {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public ColorBarAnnotation(Page page, Rectangle rect)
```


Creates new ColorBar annotation on the specified page. Default ColorsOfCMYK.Black

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Required rectangle that sets annotation's drawing area. |

### ColorBarAnnotation(Page page, Rectangle rect, int colorOfCMYK) {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-int-}
```
public ColorBarAnnotation(Page page, Rectangle rect, int colorOfCMYK)
```


Creates new ColorBar annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Required rectangle that sets annotation's drawing area. |
| colorOfCMYK | int | Color for which annotation drawing. |

### getColorOfCMYK() {#getColorOfCMYK--}
```
public final int getColorOfCMYK()
```


Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing.

**Returns:**
int - ColorsOfCMYK element
### setColorOfCMYK(int value) {#setColorOfCMYK-int-}
```
public final void setColorOfCMYK(int value)
```


Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColorsOfCMYK element |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype)
### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Update parameters and appearance, according to the matrix transform and moving outside of TrimBox if nesseary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix specifying the transformation. |

