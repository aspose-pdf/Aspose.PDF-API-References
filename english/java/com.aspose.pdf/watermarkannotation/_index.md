---
title: WatermarkAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class describes Watermark annotation object.
type: docs
weight: 401
url: /java/com.aspose.pdf/watermarkannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public class WatermarkAnnotation extends Annotation
```

Class describes Watermark annotation object.
## Constructors

| Constructor | Description |
| --- | --- |
| [WatermarkAnnotation(Page page, Rectangle rect)](#WatermarkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for Watermark annotation class. |
## Methods

| Method | Description |
| --- | --- |
| [setText(FormattedText text)](#setText-com.aspose.pdf.facades.FormattedText-) | Set text of the annotation. |
| [setTextAndState(String[] text, TextState textState)](#setTextAndState-java.lang.String---com.aspose.pdf.TextState-) | Set text of the annotation. |
| [getFixedPrint()](#getFixedPrint--) | Fixed print object of Watermark annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets annotation type. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Apply visitor for annotation. |
| [getOpacity()](#getOpacity--) | Gets or sets opacity of the annotation. |
| [setOpacity(double value)](#setOpacity-double-) | Gets or sets opacity of the annotation. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Overrides the definition in the base class with an empty body. |
### WatermarkAnnotation(Page page, Rectangle rect) {#WatermarkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public WatermarkAnnotation(Page page, Rectangle rect)
```


Constructor for Watermark annotation class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where annotation should be placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Position of the annotation. |

### setText(FormattedText text) {#setText-com.aspose.pdf.facades.FormattedText-}
```
public void setText(FormattedText text)
```


Set text of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText Text value. |

### setTextAndState(String[] text, TextState textState) {#setTextAndState-java.lang.String---com.aspose.pdf.TextState-}
```
public void setTextAndState(String[] text, TextState textState)
```


Set text of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String[] | String array (Text value) |
| textState | [TextState](../../com.aspose.pdf/textstate) | TextState object |

### getFixedPrint() {#getFixedPrint--}
```
public FixedPrint getFixedPrint()
```


Fixed print object of Watermark annotation.

**Returns:**
[FixedPrint](../../com.aspose.pdf/fixedprint) - FixedPrint object
### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets annotation type.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Apply visitor for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets or sets opacity of the annotation.

**Returns:**
double - double value
### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Gets or sets opacity of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Overrides the definition in the base class with an empty body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix specifying the transformation. |

