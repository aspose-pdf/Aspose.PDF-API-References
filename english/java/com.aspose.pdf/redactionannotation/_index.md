---
title: RedactionAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents Redact annotation.
type: docs
weight: 4120
url: /java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Represents Redact annotation.

## Constructors

| Constructor | Description |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Constructor for RedactionAnnotation. For using in Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for RedactAnnotation. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [flatten](#flatten--) | Flattens annotation i.e. removes annotation and adds its content |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getBorderColor](#getBorderColor--) | Gets color of border which is drawn when redaction is not active. |
| [getDefaultAppearance](#getDefaultAppearance--) | Gets or sets the default appearance string to be used in formatting the text. |
| [getFillColor](#getFillColor--) | Gets color to fill annotation. |
| [getFontSize](#getFontSize--) | Gets font size for OverlayText. |
| [getOverlayText](#getOverlayText--) | Gets text to print on redact annotation. |
| [getQuadPoint](#getQuadPoint--) | An array of 8xN numbers specifying the coordinates of content region that is intended to be removed. |
| [getQuadPoints](#getQuadPoints--) | Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation. |
| [getTextAlignment](#getTextAlignment--) | Gets alignment of Overlay Text. |
| [isRepeat](#isRepeat--) | If true overlay text will be repeated on the annotation. |
| [redact](#redact--) | Flattens annotation and redacts page contents (i.e. removes text and image content under redacted annotation) |
| [redactExact](#redactExact--) | Flattens annotation and redacts page contents (i.e. removes text and image content exactly under redacted annotation) |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Sets color of border which is drawn when redaction is not active. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Gets or sets the default appearance string to be used in formatting the text. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Sets color to fill annotation. |
| [setFontSize](#setFontSize-float-) | Sets font size for OverlayText. Default value is 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Sets text to print on redact annotation. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | An array of 8xN numbers specifying the coordinates of content region that is intended to be removed. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation. |
| [setRepeat](#setRepeat-boolean-) | If true overlay text will be repeated on the annotation. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets alignment of Overlay Text. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Constructor for RedactionAnnotation. For using in Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructor for RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### flatten {#flatten--}
```
public void flatten()
```

Flattens annotation i.e. removes annotation and adds its content

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Gets color of border which is drawn when redaction is not active.

**Returns:**
Color value

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Gets or sets the default appearance string to be used in formatting the text.

**Returns:**
String value

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Gets color to fill annotation.

**Returns:**
color value

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Gets font size for OverlayText.

**Returns:**
int value

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Gets text to print on redact annotation.

**Returns:**
string value

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

An array of 8xN numbers specifying the coordinates of content region that is intended to be removed.

**Returns:**
array of point

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Returns:**
array of Point value

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Gets alignment of Overlay Text.

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

If true overlay text will be repeated on the annotation.

**Returns:**
boolean value

### redact {#redact--}
```
public void redact()
```

Flattens annotation and redacts page contents (i.e. removes text and image content under redacted annotation)

### redactExact {#redactExact--}
```
public void redactExact()
```

Flattens annotation and redacts page contents (i.e. removes text and image content exactly under redacted annotation)

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Sets color of border which is drawn when redaction is not active.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Gets or sets the default appearance string to be used in formatting the text.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Sets color to fill annotation.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Sets font size for OverlayText. Default value is 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSize |  | int value |

### setOverlayText {#setOverlayText-java.lang.String-}
Sets text to print on redact annotation.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
An array of 8xN numbers specifying the coordinates of content region that is intended to be removed.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

If true overlay text will be repeated on the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets alignment of Overlay Text.
