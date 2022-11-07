---
title: TextBoxField
second_title: Aspose.PDF for Java API Reference
description: Class representing text box field.
type: docs
weight: 289
url: /java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field)
```
public class TextBoxField extends Field
```

Class representing text box field.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextBoxField()](#TextBoxField--) | Create instance of TextBoxField. |
| [TextBoxField(Page page, Rectangle rect)](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor of TextBox field. |
## Methods

| Method | Description |
| --- | --- |
| [getMultiline()](#getMultiline--) | Gets multiline flag of the field. |
| [setMultiline(boolean value)](#setMultiline-boolean-) | Sets multiline flag of the field. |
| [getSpellCheck()](#getSpellCheck--) | Gets spellcheck flag for field. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Sets spellcheck flag for field. |
| [getScrollable()](#getScrollable--) | Gets scrollable flag of field. |
| [setScrollable(boolean value)](#setScrollable-boolean-) | Sets scrollable flag of field. |
| [getForceCombs()](#getForceCombs--) | Gets flag which indicates is field divided into spaced positions. |
| [setForceCombs(boolean value)](#setForceCombs-boolean-) | Sets flag which indicates is field divided into spaced positions. |
| [getMaxLen()](#getMaxLen--) | Gets maximum length of text in the field. |
| [setMaxLen(int value)](#setMaxLen-int-) | Sets maximum length of text in the field. |
| [getValue()](#getValue--) | Gets value of the field. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets value of the field. |
| [addBarcode(String code)](#addBarcode-java.lang.String-) | Adds barcode 128 into the field. |
| [setJustification(boolean value)](#setJustification-boolean-) |  |
### TextBoxField() {#TextBoxField--}
```
public TextBoxField()
```


Create instance of TextBoxField.

### TextBoxField(Page page, Rectangle rect) {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public TextBoxField(Page page, Rectangle rect)
```


Constructor of TextBox field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where text field is placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where the text field will be placed on the page. |

### getMultiline() {#getMultiline--}
```
public boolean getMultiline()
```


Gets multiline flag of the field. If Multiline is true field can contain multiple lines of text.

**Returns:**
boolean - boolean value
### setMultiline(boolean value) {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```


Sets multiline flag of the field. If Multiline is true field can contain multiple lines of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSpellCheck() {#getSpellCheck--}
```
public boolean getSpellCheck()
```


Gets spellcheck flag for field. If true field shall be spell checked.

**Returns:**
boolean - boolean value
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```


Sets spellcheck flag for field. If true field shall be spell checked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getScrollable() {#getScrollable--}
```
public boolean getScrollable()
```


Gets scrollable flag of field. If true field can be scrolled.

**Returns:**
boolean - boolean value
### setScrollable(boolean value) {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```


Sets scrollable flag of field. If true field can be scrolled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getForceCombs() {#getForceCombs--}
```
public boolean getForceCombs()
```


Gets flag which indicates is field divided into spaced positions.

**Returns:**
boolean - boolean value
### setForceCombs(boolean value) {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```


Sets flag which indicates is field divided into spaced positions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMaxLen() {#getMaxLen--}
```
public int getMaxLen()
```


Gets maximum length of text in the field.

**Returns:**
int - int value
### setMaxLen(int value) {#setMaxLen-int-}
```
public void setMaxLen(int value)
```


Sets maximum length of text in the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getValue() {#getValue--}
```
public String getValue()
```


Gets value of the field.

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets value of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### addBarcode(String code) {#addBarcode-java.lang.String-}
```
public void addBarcode(String code)
```


Adds barcode 128 into the field. Field value will be changed onto the code and field become read only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String | The text to generate barcode 128. |

### setJustification(boolean value) {#setJustification-boolean-}
```
public void setJustification(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

