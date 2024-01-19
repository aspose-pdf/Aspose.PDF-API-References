---
title: FreeTextAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a free text annotation that displays text directly on the page.
type: docs
weight: 142
url: /java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible.
## Constructors

| Constructor | Description |
| --- | --- |
| [FreeTextAnnotation(IDocument document, DefaultAppearance appearance)](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Constructor to use with Generator. |
| [FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance)](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Creates new FreeText annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getStartingStyle()](#getStartingStyle--) | Gets or sets line ending style for line ending point. |
| [setStartingStyle(int value)](#setStartingStyle-int-) | Gets or sets line ending style for line ending point. |
| [getEndingStyle()](#getEndingStyle--) | Gets line ending style for line ending point. |
| [setEndingStyle(int value)](#setEndingStyle-int-) | Sets line ending style for line ending point. |
| [getJustification()](#getJustification--) | Gets a code specifying the form of quadding (justification) to be used in displaying the annotation's text. |
| [setJustification(int value)](#setJustification-int-) | Sets a code specifying the form of quadding (justification) to be used in displaying the annotation's text. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets the default appearance string to be used in formatting the text. |
| [setDefaultAppearance(String value)](#setDefaultAppearance-java.lang.String-) | Sets the default appearance string to be used in formatting the text. |
| [getDefaultAppearanceObject()](#getDefaultAppearanceObject--) | Object which represents default appearance of FreeText annotation. |
| [getIntent()](#getIntent--) | Gets the intent of the free text annotation. |
| [setIntent(int value)](#setIntent-int-) | Sets the intent of the free text annotation. |
| [getDefaultStyle()](#getDefaultStyle--) | Gets a default style string. |
| [setDefaultStyle(String value)](#setDefaultStyle-java.lang.String-) | Sets a default style string. |
| [getTextStyle()](#getTextStyle--) | Gets or sets style of the text in appearance. |
| [setTextStyle(TextStyle value)](#setTextStyle-com.aspose.pdf.TextStyle-) | Sets style of the text in appearance. |
| [getRotate()](#getRotate--) | Angle of annotation rotation. |
| [setRotate(int value)](#setRotate-int-) | Angle of annotation rotation. |
| [updateAppearance()](#updateAppearance--) | Updates the Appearance, after text has been changed/moved. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [getCallout()](#getCallout--) | Array of point specifying callout line. |
| [setCallout(Point[] value)](#setCallout-com.aspose.pdf.Point---) | Array of point specifying callout line. |
| [getTextRectangle()](#getTextRectangle--) | Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. |
| [setTextRectangle(Rectangle value)](#setTextRectangle-com.aspose.pdf.Rectangle-) | Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. |
### FreeTextAnnotation(IDocument document, DefaultAppearance appearance) {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
```
public FreeTextAnnotation(IDocument document, DefaultAppearance appearance)
```


Constructor to use with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be created. |
| appearance | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | Default Appearance |

### FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance) {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
```
public FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance)
```


Creates new FreeText annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| appearance | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | The default appearance string to be used in formatting the text. |

### getStartingStyle() {#getStartingStyle--}
```
public final int getStartingStyle()
```


Gets or sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle.

**Returns:**
int - LineEnding element
### setStartingStyle(int value) {#setStartingStyle-int-}
```
public final void setStartingStyle(int value)
```


Gets or sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding element |

### getEndingStyle() {#getEndingStyle--}
```
public int getEndingStyle()
```


Gets line ending style for line ending point.

**Returns:**
int - LineEnding value
### setEndingStyle(int value) {#setEndingStyle-int-}
```
public void setEndingStyle(int value)
```


Sets line ending style for line ending point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding value |

### getJustification() {#getJustification--}
```
public int getJustification()
```


Gets a code specifying the form of quadding (justification) to be used in displaying the annotation's text.

**Returns:**
int - int value
### setJustification(int value) {#setJustification-int-}
```
public void setJustification(int value)
```


Sets a code specifying the form of quadding (justification) to be used in displaying the annotation's text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```


Gets the default appearance string to be used in formatting the text.

**Returns:**
java.lang.String - String value
### setDefaultAppearance(String value) {#setDefaultAppearance-java.lang.String-}
```
public void setDefaultAppearance(String value)
```


Sets the default appearance string to be used in formatting the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDefaultAppearanceObject() {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```


Object which represents default appearance of FreeText annotation.

**Returns:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - DefaultAppearance object
### getIntent() {#getIntent--}
```
public int getIntent()
```


Gets the intent of the free text annotation.

**Returns:**
int - int value
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Sets the intent of the free text annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getDefaultStyle() {#getDefaultStyle--}
```
public String getDefaultStyle()
```


Gets a default style string.

**Returns:**
java.lang.String - String value
### setDefaultStyle(String value) {#setDefaultStyle-java.lang.String-}
```
public void setDefaultStyle(String value)
```


Sets a default style string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getTextStyle() {#getTextStyle--}
```
public TextStyle getTextStyle()
```


Gets or sets style of the text in appearance. when text style is changed, text appearance is updated.

**Returns:**
[TextStyle](../../com.aspose.pdf/textstyle) - TextStyle value
### setTextStyle(TextStyle value) {#setTextStyle-com.aspose.pdf.TextStyle-}
```
public void setTextStyle(TextStyle value)
```


Sets style of the text in appearance. when text style is changed, text appearance is updated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextStyle](../../com.aspose.pdf/textstyle) | TextStyle object |

### getRotate() {#getRotate--}
```
public int getRotate()
```


Angle of annotation rotation.

**Returns:**
int - Rotation element
### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Angle of annotation rotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Rotation element |

### updateAppearance() {#updateAppearance--}
```
public void updateAppearance()
```


Updates the Appearance, after text has been changed/moved.

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - int value
### getCallout() {#getCallout--}
```
public final Point[] getCallout()
```


Array of point specifying callout line.

**Returns:**
com.aspose.pdf.Point[] - array of Point
### setCallout(Point[] value) {#setCallout-com.aspose.pdf.Point---}
```
public final void setCallout(Point[] value)
```


Array of point specifying callout line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | array of Point |

### getTextRectangle() {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```


Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation\\ufffds text should be displayed.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle instance
### setTextRectangle(Rectangle value) {#setTextRectangle-com.aspose.pdf.Rectangle-}
```
public final void setTextRectangle(Rectangle value)
```


Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation\\ufffds text should be displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle instance |

