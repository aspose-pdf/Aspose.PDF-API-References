---
title: FreeTextAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of.
type: docs
weight: 1790
url: /java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible.

## Constructors

| Constructor | Description |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Constructor to use with Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Creates new FreeText annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getCallout](#getCallout--) | Array of point specifying callout line. |
| [getDefaultAppearance](#getDefaultAppearance--) | Gets the default appearance string to be used in formatting the text. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Object which represents default appearance of FreeText annotation. |
| [getDefaultStyle](#getDefaultStyle--) | Gets a default style string. |
| [getEndingStyle](#getEndingStyle--) | Gets line ending style for line ending point. |
| [getIntent](#getIntent--) | Gets the intent of the free text annotation. |
| [getJustification](#getJustification--) | Gets a code specifying the form of quadding (justification) to be used in displaying the annotation's text. |
| [getRotate](#getRotate--) | Angle of annotation rotation. |
| [getStartingStyle](#getStartingStyle--) | Gets or sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation's text should be displayed. |
| [getTextStyle](#getTextStyle--) | Gets or sets style of the text in appearance. when text style is changed, text appearance is updated. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Array of point specifying callout line. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Sets the default appearance string to be used in formatting the text. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Sets a default style string. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Sets line ending style for line ending point. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Sets the intent of the free text annotation. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Sets a code specifying the form of quadding (justification) to be used in displaying the annotation's text. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Angle of annotation rotation. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Gets or sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation's text should be displayed. |
| [setTextStyle](#setTextStyle-int-int-int-) | Sets the formatting determined by the parameter textStyle for a text fragment from fromInd index to toInd index. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Sets the formatting determined by the parameter textStyle for all annotation text. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Sets style of the text in appearance. when text style is changed, text appearance is updated. |
| [updateAppearance](#updateAppearance--) | Updates the Appearance, after text has been changed/moved. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Constructor to use with Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Creates new FreeText annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
int value

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Array of point specifying callout line.

**Returns:**
array of Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Gets the default appearance string to be used in formatting the text.

**Returns:**
String value

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Object which represents default appearance of FreeText annotation.

**Returns:**
DefaultAppearance object

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Gets a default style string.

**Returns:**
String value

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Gets line ending style for line ending point.

**Returns:**
LineEnding value @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Gets the intent of the free text annotation.

**Returns:**
int value @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Gets a code specifying the form of quadding (justification) to be used in displaying the annotation's text.

**Returns:**
int value @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Angle of annotation rotation.

**Returns:**
Rotation element @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Gets or sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle.

**Returns:**
LineEnding element

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation's text should be displayed.

**Returns:**
Rectangle instance

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Gets or sets style of the text in appearance. when text style is changed, text appearance is updated.

**Returns:**
TextStyle value

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Array of point specifying callout line.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Sets the default appearance string to be used in formatting the text.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Sets a default style string.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Sets line ending style for line ending point.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Sets the intent of the free text annotation.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Sets a code specifying the form of quadding (justification) to be used in displaying the annotation's text.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Angle of annotation rotation.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Gets or sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation's text should be displayed.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Sets the formatting determined by the parameter textStyle for a text fragment from fromInd index to toInd index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fromInd |  | Starting index of the text fragment (from 0). |
| toInd |  | End index of the text fragment (counting from 0, this not included). |
| textStyles |  | Style(s) applied for text fragment. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Sets the formatting determined by the parameter textStyle for all annotation text.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Sets style of the text in appearance. when text style is changed, text appearance is updated.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Updates the Appearance, after text has been changed/moved.
