---
title: NumberField
second_title: Aspose.PDF for Java API Reference
description: Text Field with specified valid chars
type: docs
weight: 227
url: /java/com.aspose.pdf/numberfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field), [com.aspose.pdf.TextBoxField](../../com.aspose.pdf/textboxfield)
```
public class NumberField extends TextBoxField
```

Text Field with specified valid chars
## Constructors

| Constructor | Description |
| --- | --- |
| [NumberField()](#NumberField--) | Initializes a new instance of the [NumberField](../../com.aspose.pdf/numberfield) class. |
| [NumberField(Page page, Rectangle rect)](#NumberField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes a new instance of the [NumberField](../../com.aspose.pdf/numberfield) class. |
| [NumberField(Document doc, Rectangle rect)](#NumberField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-) | Initializes a new instance of the [NumberField](../../com.aspose.pdf/numberfield) class. |
## Methods

| Method | Description |
| --- | --- |
| [getAllowedChars()](#getAllowedChars--) | Gets or sets the allowed chars. |
| [setAllowedChars(String value)](#setAllowedChars-java.lang.String-) | Gets or sets the allowed chars. |
### NumberField() {#NumberField--}
```
public NumberField()
```


Initializes a new instance of the [NumberField](../../com.aspose.pdf/numberfield) class.

### NumberField(Page page, Rectangle rect) {#NumberField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public NumberField(Page page, Rectangle rect)
```


Initializes a new instance of the [NumberField](../../com.aspose.pdf/numberfield) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where text field is placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where the field will be placed on the page. |

### NumberField(Document doc, Rectangle rect) {#NumberField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-}
```
public NumberField(Document doc, Rectangle rect)
```


Initializes a new instance of the [NumberField](../../com.aspose.pdf/numberfield) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Document where field will be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle of the field. |

### getAllowedChars() {#getAllowedChars--}
```
public final String getAllowedChars()
```


Gets or sets the allowed chars.

Value: The allowed chars string. 0123456789 by default

**Returns:**
java.lang.String - String value
### setAllowedChars(String value) {#setAllowedChars-java.lang.String-}
```
public final void setAllowedChars(String value)
```


Gets or sets the allowed chars.

Value: The allowed chars string. 0123456789 by default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

