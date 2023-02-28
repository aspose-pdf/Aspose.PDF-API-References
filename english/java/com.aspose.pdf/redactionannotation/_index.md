---
title: RedactionAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents Redact annotation.
type: docs
weight: 302
url: /java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class RedactionAnnotation extends MarkupAnnotation
```

Represents Redact annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [RedactionAnnotation(IDocument document)](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Constructor for RedactionAnnotation. |
| [RedactionAnnotation(Page page, Rectangle rect)](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for RedactAnnotation. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getQuadPoint()](#getQuadPoint--) | An array of 8xN numbers specifying the coordinates of content region that is intended to be removed. |
| [setQuadPoint(Point[] value)](#setQuadPoint-com.aspose.pdf.Point---) | An array of 8xN numbers specifying the coordinates of content region that is intended to be removed. |
| [getQuadPoints()](#getQuadPoints--) | Gets an array of points specifying the coordinates of n quadrilaterals. |
| [setQuadPoints(Point[] value)](#setQuadPoints-com.aspose.pdf.Point---) | Sets an array of points specifying the coordinates of n quadrilaterals. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets or sets the default appearance string to be used in formatting the text. |
| [setDefaultAppearance(String value)](#setDefaultAppearance-java.lang.String-) | Gets or sets the default appearance string to be used in formatting the text. |
| [getFillColor()](#getFillColor--) | Gets color to fill annotation. |
| [setFillColor(Color value)](#setFillColor-com.aspose.pdf.Color-) | Sets color to fill annotation. |
| [getBorderColor()](#getBorderColor--) | Gets color of border which is drawn when redaction is not active. |
| [setBorderColor(Color value)](#setBorderColor-com.aspose.pdf.Color-) | Sets color of border which is drawn when redaction is not active. |
| [getOverlayText()](#getOverlayText--) | Text to print on redact annotation. |
| [setOverlayText(String value)](#setOverlayText-java.lang.String-) | Text to print on redact annotation. |
| [isRepeat()](#isRepeat--) | If true overlay text will be repated on the annotation. |
| [setRepeat(boolean value)](#setRepeat-boolean-) | If true overlay text will be repated on the annotation. |
| [getTextAlignment()](#getTextAlignment--) | Gets alignment of Overlay Text. |
| [setTextAlignment(HorizontalAlignment value)](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets alignment of Overlay Text. |
| [flatten()](#flatten--) | Flattens annotation i.e. removes annotation and adds its content |
| [redact()](#redact--) | Flattens annotation and redacts page contents (i.e. removes text and image content under redacted annotation) |
| [redactExact()](#redactExact--) | Flattens annotation and redacts page contents (i.e. removes text and image content exactly under redacted annotation) |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [setFontSize(double fontSize)](#setFontSize-double-) | Font size of text to print on redact annotation. |
### RedactionAnnotation(IDocument document) {#RedactionAnnotation-com.aspose.pdf.IDocument-}
```
public RedactionAnnotation(IDocument document)
```


Constructor for RedactionAnnotation. For using in Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where new annotation will be created. |

### RedactionAnnotation(Page page, Rectangle rect) {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public RedactionAnnotation(Page page, Rectangle rect)
```


Constructor for RedactAnnotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where annotation will be placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Annotation position on the page. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getQuadPoint() {#getQuadPoint--}
```
public Point[] getQuadPoint()
```


An array of 8xN numbers specifying the coordinates of content region that is intended to be removed.

**Returns:**
com.aspose.pdf.Point[] - array of point
### setQuadPoint(Point[] value) {#setQuadPoint-com.aspose.pdf.Point---}
```
public void setQuadPoint(Point[] value)
```


An array of 8xN numbers specifying the coordinates of content region that is intended to be removed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | array of point |

### getQuadPoints() {#getQuadPoints--}
```
public Point[] getQuadPoints()
```


Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Returns:**
com.aspose.pdf.Point[] - array of Point value
### setQuadPoints(Point[] value) {#setQuadPoints-com.aspose.pdf.Point---}
```
public void setQuadPoints(Point[] value)
```


Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | array of Point value |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```


Gets or sets the default appearance string to be used in formatting the text.

**Returns:**
java.lang.String - String value
### setDefaultAppearance(String value) {#setDefaultAppearance-java.lang.String-}
```
public final void setDefaultAppearance(String value)
```


Gets or sets the default appearance string to be used in formatting the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFillColor() {#getFillColor--}
```
public Color getFillColor()
```


Gets color to fill annotation.

**Returns:**
[Color](../../com.aspose.pdf/color) - color value
### setFillColor(Color value) {#setFillColor-com.aspose.pdf.Color-}
```
public void setFillColor(Color value)
```


Sets color to fill annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | color value |

### getBorderColor() {#getBorderColor--}
```
public Color getBorderColor()
```


Gets color of border which is drawn when redaction is not active.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color value
### setBorderColor(Color value) {#setBorderColor-com.aspose.pdf.Color-}
```
public void setBorderColor(Color value)
```


Sets color of border which is drawn when redaction is not active.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color value |

### getOverlayText() {#getOverlayText--}
```
public String getOverlayText()
```


Text to print on redact annotation.

**Returns:**
java.lang.String - string value
### setOverlayText(String value) {#setOverlayText-java.lang.String-}
```
public void setOverlayText(String value)
```


Text to print on redact annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string object |

### isRepeat() {#isRepeat--}
```
public boolean isRepeat()
```


If true overlay text will be repated on the annotation.

**Returns:**
boolean - boolean value
### setRepeat(boolean value) {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```


If true overlay text will be repated on the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getTextAlignment() {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```


Gets alignment of Overlay Text.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - HorizontalAlignment value
### setTextAlignment(HorizontalAlignment value) {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public void setTextAlignment(HorizontalAlignment value)
```


Sets alignment of Overlay Text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | HorizontalAlignment value |

### flatten() {#flatten--}
```
public void flatten()
```


Flattens annotation i.e. removes annotation and adds its content

### redact() {#redact--}
```
public void redact()
```


Flattens annotation and redacts page contents (i.e. removes text and image content under redacted annotation)

### redactExact() {#redactExact--}
```
public void redactExact()
```


Flattens annotation and redacts page contents (i.e. removes text and image content exactly under redacted annotation)

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
### setFontSize(double fontSize) {#setFontSize-double-}
```
public void setFontSize(double fontSize)
```


Font size of text to print on redact annotation.

Default value is 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize | double | int value |

