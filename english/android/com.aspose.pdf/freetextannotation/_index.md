---
title: FreeTextAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a free text annotation that displays text directly on the page.
type: docs
weight: 120
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
| [FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance)](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Creates new FreeText annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getStartingStyle()](#getStartingStyle--) | Gets or sets line ending style for line starting point. |
| [setStartingStyle(int value)](#setStartingStyle-int-) |  |
| [getEndingStyle()](#getEndingStyle--) | Gets or sets line ending style for line ending point. |
| [setEndingStyle(int value)](#setEndingStyle-int-) |  |
| [getJustification()](#getJustification--) | Gets a code specifying the form of quadding (justification) to be used in displaying the annotation\\ufffds text. |
| [setJustification(int value)](#setJustification-int-) | Sets a code specifying the form of quadding (justification) to be used in displaying the annotation\\ufffds text. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets the default appearance string to be used in formatting the text. |
| [setDefaultAppearance(String value)](#setDefaultAppearance-java.lang.String-) | Sets the default appearance string to be used in formatting the text. |
| [getDefaultAppearanceObject()](#getDefaultAppearanceObject--) | Object which represents default appearance of FreeText annotation. |
| [getIntent()](#getIntent--) | Gets the intent of the free text annotation. |
| [setIntent(int value)](#setIntent-int-) | Sets the intent of the free text annotation. |
| [getDefaultStyle()](#getDefaultStyle--) | Gets a default style string. |
| [setDefaultStyle(String value)](#setDefaultStyle-java.lang.String-) | Sets a default style string. |
| [getTextStyle()](#getTextStyle--) | Gets or sets style of the text in appearance. when text style is changed, text appearance is updated. |
| [setTextStyle(TextStyle value)](#setTextStyle-com.aspose.pdf.TextStyle-) | Sets style of the text in appearance. when text style is changed, text appearance is updated. |
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
public int getStartingStyle()
```


Gets or sets line ending style for line starting point.

**Returns:**
int
### setStartingStyle(int value) {#setStartingStyle-int-}
```
public void setStartingStyle(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndingStyle() {#getEndingStyle--}
```
public int getEndingStyle()
```


Gets or sets line ending style for line ending point.

**Returns:**
int
### setEndingStyle(int value) {#setEndingStyle-int-}
```
public void setEndingStyle(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getJustification() {#getJustification--}
```
public int getJustification()
```


Gets a code specifying the form of quadding (justification) to be used in displaying the annotation\\ufffds text.

**Returns:**
int
### setJustification(int value) {#setJustification-int-}
```
public void setJustification(int value)
```


Sets a code specifying the form of quadding (justification) to be used in displaying the annotation\\ufffds text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
java.lang.String
### setDefaultAppearance(String value) {#setDefaultAppearance-java.lang.String-}
```
public void setDefaultAppearance(String value)
```


Sets the default appearance string to be used in formatting the text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAppearanceObject() {#getDefaultAppearanceObject--}
```
public DefaultAppearance getDefaultAppearanceObject()
```


Object which represents default appearance of FreeText annotation.

**Returns:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance)
### getIntent() {#getIntent--}
```
public int getIntent()
```


Gets the intent of the free text annotation.

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Sets the intent of the free text annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultStyle() {#getDefaultStyle--}
```
public String getDefaultStyle()
```


Gets a default style string.

**Returns:**
java.lang.String
### setDefaultStyle(String value) {#setDefaultStyle-java.lang.String-}
```
public void setDefaultStyle(String value)
```


Sets a default style string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextStyle() {#getTextStyle--}
```
public TextStyle getTextStyle()
```


Gets or sets style of the text in appearance. when text style is changed, text appearance is updated.

**Returns:**
[TextStyle](../../com.aspose.pdf/textstyle)
### setTextStyle(TextStyle value) {#setTextStyle-com.aspose.pdf.TextStyle-}
```
public void setTextStyle(TextStyle value)
```


Sets style of the text in appearance. when text style is changed, text appearance is updated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextStyle](../../com.aspose.pdf/textstyle) |  |

