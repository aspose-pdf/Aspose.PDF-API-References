---
title: LineAnnotation
linktitle: LineAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing line annotation.
type: docs
weight: 2710
url: /java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Class representing line annotation.

## Constructors

| Constructor | Description |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Constructor for using with Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Creates new Line annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor to annotation processing. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the Starting and Ending points, according to the matrix transform. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getCaptionOffset](#getCaptionOffset--) | Gets caption text offset from its normal position. |
| [getCaptionPosition](#getCaptionPosition--) | Gets annotation caption position. |
| [getEnding](#getEnding--) | Gets line ending point. |
| [getEndingStyle](#getEndingStyle--) | Gets ending style for end point of line. |
| [getIntent](#getIntent--) | Gets the intent of the line annotation. |
| [getInteriorColor](#getInteriorColor--) | Gets interior color of the annotation. |
| [getLeaderLine](#getLeaderLine--) | Gets leader line length. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Gets length of leader line extension. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Gets leader line offset. |
| [getMeasure](#getMeasure--) | Measure units specifed for this annotation. |
| [getShowCaption](#getShowCaption--) | Gets boolean flag which determinies is contents must be shown as caption. |
| [getStarting](#getStarting--) | Gets starting point of line. |
| [getStartingStyle](#getStartingStyle--) | Gets line ending style for line starting point. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Sets caption text offset from its normal position. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Sets annotation caption position. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Sets line ending point. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Sets ending style for end point of line. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Sets the intent of the line annotation. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Sets interior color of the annotation. |
| [setLeaderLine](#setLeaderLine-double-) | Sets leader line length. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Sets length of leader line extension. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Sets leader line offset. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Measure units specifed for this annotation. |
| [setShowCaption](#setShowCaption-boolean-) | Sets boolean flag which determinies is contents must be shown as caption. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Sets starting point of line. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Sets line ending style for line starting point. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Constructor for using with Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Creates new Line annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor to annotation processing.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Updates the Starting and Ending points, according to the matrix transform.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Gets caption text offset from its normal position.

**Returns:**
Point object

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Gets annotation caption position.

**Returns:**
CaptionPosition element @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Gets line ending point.

**Returns:**
Point value

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Gets ending style for end point of line.

**Returns:**
LineEnding element @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Gets the intent of the line annotation.

**Returns:**
LineIntent element @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Gets interior color of the annotation.

**Returns:**
Color object

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Gets leader line length.

**Returns:**
double value

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Gets length of leader line extension.

**Returns:**
double value

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Gets leader line offset.

**Returns:**
double value

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Measure units specifed for this annotation.

**Returns:**
Measure object

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Gets boolean flag which determinies is contents must be shown as caption.

**Returns:**
boolean value

### getStarting {#getStarting--}
```
public Point getStarting()
```

Gets starting point of line.

**Returns:**
Point value

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Gets line ending style for line starting point.

**Returns:**
LineEnding element @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Sets caption text offset from its normal position.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Sets annotation caption position.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Sets line ending point.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Sets ending style for end point of line.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Sets the intent of the line annotation.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Sets interior color of the annotation.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Sets leader line length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Sets length of leader line extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Sets leader line offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Measure units specifed for this annotation.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Sets boolean flag which determinies is contents must be shown as caption.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Sets starting point of line.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Sets line ending style for line starting point.
