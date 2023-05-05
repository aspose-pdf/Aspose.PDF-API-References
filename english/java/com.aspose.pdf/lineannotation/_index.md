---
title: LineAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing line annotation.
type: docs
weight: 194
url: /java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class LineAnnotation extends MarkupAnnotation
```

Class representing line annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [LineAnnotation(IDocument document, Point start, Point end)](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Constructor for using with Generator. |
| [LineAnnotation(Page page, Rectangle rect, Point start, Point end)](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Creates new Line annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getStarting()](#getStarting--) | Gets starting point of line. |
| [setStarting(Point value)](#setStarting-com.aspose.pdf.Point-) | Sets starting point of line. |
| [getStartingStyle()](#getStartingStyle--) | Gets line ending style for line starting point. |
| [setStartingStyle(int value)](#setStartingStyle-int-) | Sets line ending style for line starting point. |
| [getEnding()](#getEnding--) | Gets line ending point. |
| [setEnding(Point value)](#setEnding-com.aspose.pdf.Point-) | Sets line ending point. |
| [getEndingStyle()](#getEndingStyle--) | Gets ending style for end point of line. |
| [setEndingStyle(int value)](#setEndingStyle-int-) | Sets ending style for end point of line. |
| [getInteriorColor()](#getInteriorColor--) | Gets interior color of the annotation. |
| [setInteriorColor(Color value)](#setInteriorColor-com.aspose.pdf.Color-) | Sets interior color of the annotation. |
| [getLeaderLine()](#getLeaderLine--) | Gets leader line length. |
| [setLeaderLine(double value)](#setLeaderLine-double-) | Sets leader line length. |
| [getLeaderLineExtension()](#getLeaderLineExtension--) | Gets length of leader line extension. |
| [setLeaderLineExtension(double value)](#setLeaderLineExtension-double-) | Sets length of leader line extension. |
| [getShowCaption()](#getShowCaption--) | Gets boolean flag which determinies is contents must be shown as caption. |
| [setShowCaption(boolean value)](#setShowCaption-boolean-) | Sets boolean flag which determinies is contents must be shown as caption. |
| [getLeaderLineOffset()](#getLeaderLineOffset--) | Gets leader line offset. |
| [setLeaderLineOffset(double value)](#setLeaderLineOffset-double-) | Sets leader line offset. |
| [getCaptionOffset()](#getCaptionOffset--) | Gets caption text offset from its normal position. |
| [setCaptionOffset(Point value)](#setCaptionOffset-com.aspose.pdf.Point-) | Sets caption text offset from its normal position. |
| [getCaptionPosition()](#getCaptionPosition--) | Gets annotation caption position. |
| [setCaptionPosition(int value)](#setCaptionPosition-int-) | Sets annotation caption position. |
| [getMeasure()](#getMeasure--) | Measure units specifed for this annotation. |
| [setMeasure(Measure value)](#setMeasure-com.aspose.pdf.Measure-) | Measure units specifed for this annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor to annotation processing. |
| [getIntent()](#getIntent--) | Gets the intent of the line annotation. |
| [setIntent(int value)](#setIntent-int-) | Sets the intent of the line annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the Starting and Ending points, according to the matrix transform. |
### LineAnnotation(IDocument document, Point start, Point end) {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
```
public LineAnnotation(IDocument document, Point start, Point end)
```


Constructor for using with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be created. |
| start | [Point](../../com.aspose.pdf/point) | Starting point. |
| end | [Point](../../com.aspose.pdf/point) | Ending point. |

### LineAnnotation(Page page, Rectangle rect, Point start, Point end) {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
```
public LineAnnotation(Page page, Rectangle rect, Point start, Point end)
```


Creates new Line annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| start | [Point](../../com.aspose.pdf/point) | A point, specifying the starting coordinate of the line. |
| end | [Point](../../com.aspose.pdf/point) | A point, specifying the ending coordinate of the line. |

### getStarting() {#getStarting--}
```
public Point getStarting()
```


Gets starting point of line.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point value
### setStarting(Point value) {#setStarting-com.aspose.pdf.Point-}
```
public void setStarting(Point value)
```


Sets starting point of line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | Point value |

### getStartingStyle() {#getStartingStyle--}
```
public int getStartingStyle()
```


Gets line ending style for line starting point.

**Returns:**
int - LineEnding element
### setStartingStyle(int value) {#setStartingStyle-int-}
```
public void setStartingStyle(int value)
```


Sets line ending style for line starting point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding element |

### getEnding() {#getEnding--}
```
public Point getEnding()
```


Gets line ending point.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point value
### setEnding(Point value) {#setEnding-com.aspose.pdf.Point-}
```
public void setEnding(Point value)
```


Sets line ending point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | Point value |

### getEndingStyle() {#getEndingStyle--}
```
public int getEndingStyle()
```


Gets ending style for end point of line.

**Returns:**
int - LineEnding element
### setEndingStyle(int value) {#setEndingStyle-int-}
```
public void setEndingStyle(int value)
```


Sets ending style for end point of line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding element |

### getInteriorColor() {#getInteriorColor--}
```
public Color getInteriorColor()
```


Gets interior color of the annotation.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### setInteriorColor(Color value) {#setInteriorColor-com.aspose.pdf.Color-}
```
public void setInteriorColor(Color value)
```


Sets interior color of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### getLeaderLine() {#getLeaderLine--}
```
public double getLeaderLine()
```


Gets leader line length.

**Returns:**
double - double value
### setLeaderLine(double value) {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```


Sets leader line length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getLeaderLineExtension() {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```


Gets length of leader line extension.

**Returns:**
double - double value
### setLeaderLineExtension(double value) {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```


Sets length of leader line extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getShowCaption() {#getShowCaption--}
```
public boolean getShowCaption()
```


Gets boolean flag which determinies is contents must be shown as caption.

**Returns:**
boolean - boolean value
### setShowCaption(boolean value) {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```


Sets boolean flag which determinies is contents must be shown as caption.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLeaderLineOffset() {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```


Gets leader line offset.

**Returns:**
double - double value
### setLeaderLineOffset(double value) {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```


Sets leader line offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getCaptionOffset() {#getCaptionOffset--}
```
public Point getCaptionOffset()
```


Gets caption text offset from its normal position.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point object
### setCaptionOffset(Point value) {#setCaptionOffset-com.aspose.pdf.Point-}
```
public void setCaptionOffset(Point value)
```


Sets caption text offset from its normal position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | Point object |

### getCaptionPosition() {#getCaptionPosition--}
```
public int getCaptionPosition()
```


Gets annotation caption position.

**Returns:**
int - CaptionPosition element
### setCaptionPosition(int value) {#setCaptionPosition-int-}
```
public void setCaptionPosition(int value)
```


Sets annotation caption position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | CaptionPosition element |

### getMeasure() {#getMeasure--}
```
public Measure getMeasure()
```


Measure units specifed for this annotation.

**Returns:**
[Measure](../../com.aspose.pdf/measure) - Measure object
### setMeasure(Measure value) {#setMeasure-com.aspose.pdf.Measure-}
```
public void setMeasure(Measure value)
```


Measure units specifed for this annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Measure](../../com.aspose.pdf/measure) | Measure object |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor to annotation processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Gets the intent of the line annotation.

**Returns:**
int - LineIntent element
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Sets the intent of the line annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineIntent element |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Updates the Starting and Ending points, according to the matrix transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix specifying the transformation. |

