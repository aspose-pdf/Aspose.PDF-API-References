---
title: DateField
second_title: Aspose.PDF for Java API Reference
description: Date field with calendar view.
type: docs
weight: 82
url: /java/com.aspose.pdf/datefield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field), [com.aspose.pdf.TextBoxField](../../com.aspose.pdf/textboxfield)
```
public class DateField extends TextBoxField
```

Date field with calendar view.

```
DateField dateField = new DateField(page, rect);
 doc.getForm().add(dateField);
 dateField.init(page);
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DateField()](#DateField--) | Initializes a new instance of the [DateField](../../com.aspose.pdf/datefield) |
| [DateField(Document doc)](#DateField-com.aspose.pdf.Document-) | Constructor which should be used with Generator. |
| [DateField(Page page, Rectangle rect)](#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes a new instance of the [DateField](../../com.aspose.pdf/datefield) |
| [DateField(Document doc, Rectangle rect)](#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-) | Initializes a new instance of the [DateField](../../com.aspose.pdf/datefield) |
## Methods

| Method | Description |
| --- | --- |
| [getValue_DateField_New()](#getValue-DateField-New--) | Gets or sets Date. |
| [setValue_DateField_New(Date value)](#setValue-DateField-New-java.util.Date-) | Gets or sets Date. |
| [getDateFormat()](#getDateFormat--) | Gets or sets the date format. |
| [setDateFormat(String value)](#setDateFormat-java.lang.String-) | Gets or sets the date format. |
| [init(Page page)](#init-com.aspose.pdf.Page-) | Initializes the JS Action. |
| [addImage_DateField_New(BufferedImage image)](#addImage-DateField-New-java.awt.image.BufferedImage-) | Image adding denied for this field. |
### DateField() {#DateField--}
```
public DateField()
```


Initializes a new instance of the [DateField](../../com.aspose.pdf/datefield)

### DateField(Document doc) {#DateField-com.aspose.pdf.Document-}
```
public DateField(Document doc)
```


Constructor which should be used with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Document where field will be created. |

### DateField(Page page, Rectangle rect) {#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public DateField(Page page, Rectangle rect)
```


Initializes a new instance of the [DateField](../../com.aspose.pdf/datefield)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page needed for create. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where the text field will be placed on the page. |

### DateField(Document doc, Rectangle rect) {#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-}
```
public DateField(Document doc, Rectangle rect)
```


Initializes a new instance of the [DateField](../../com.aspose.pdf/datefield)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Document where field will be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle of the field. |

### getValue_DateField_New() {#getValue-DateField-New--}
```
public final Date getValue_DateField_New()
```


Gets or sets Date.

**Returns:**
[Date](../../java.util/date) - java.util.Date instance
### setValue_DateField_New(Date value) {#setValue-DateField-New-java.util.Date-}
```
public final void setValue_DateField_New(Date value)
```


Gets or sets Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | java.util.Date instance |

### getDateFormat() {#getDateFormat--}
```
public final String getDateFormat()
```


Gets or sets the date format.

Value: The date format. Default dd/MM/yyyy

**Returns:**
java.lang.String - String value
### setDateFormat(String value) {#setDateFormat-java.lang.String-}
```
public final void setDateFormat(String value)
```


Gets or sets the date format.

Value: The date format. Default dd/MM/yyyy

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### init(Page page) {#init-com.aspose.pdf.Page-}
```
public final void init(Page page)
```


Initializes the JS Action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page. |

### addImage_DateField_New(BufferedImage image) {#addImage-DateField-New-java.awt.image.BufferedImage-}
```
public final void addImage_DateField_New(BufferedImage image)
```


Image adding denied for this field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | The image. |

