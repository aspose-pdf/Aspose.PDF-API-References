---
title: CheckboxField
second_title: Aspose.PDF for Java API Reference
description: Class representing checkbox field
type: docs
weight: 55
url: /java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field)
```
public final class CheckboxField extends Field
```

Class representing checkbox field
## Constructors

| Constructor | Description |
| --- | --- |
| [CheckboxField(Page page, Rectangle rect)](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for CheckboxField class. |
| [CheckboxField()](#CheckboxField--) | Create instance of CheckboxField. |
## Methods

| Method | Description |
| --- | --- |
| [getOnState()](#getOnState--) | Returns name of state which is "Checked" state of checkbox. |
| [getStyle()](#getStyle--) | Gets or sets style of check box. |
| [setStyle(int value)](#setStyle-int-) |  |
| [getActiveState()](#getActiveState--) | Gets current annotation appearance state. |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [getChecked()](#getChecked--) | Gets state of check box. |
| [setChecked(boolean value)](#setChecked-boolean-) | Sets state of check box. |
| [getNormalCaption()](#getNormalCaption--) | Gets normal caption of the field. |
| [getValue()](#getValue--) | Gets value of check box field. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets value of check box field. |
### CheckboxField(Page page, Rectangle rect) {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public CheckboxField(Page page, Rectangle rect)
```


Constructor for CheckboxField class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where check box will be placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Position and size of the check box. |

### CheckboxField() {#CheckboxField--}
```
public CheckboxField()
```


Create instance of CheckboxField.

### getOnState() {#getOnState--}
```
public String getOnState()
```


Returns name of state which is "Checked" state of checkbox. This is "Yes" if presents or any other value other then "Off" and "No";

**Returns:**
java.lang.String - 
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets or sets style of check box.

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


Gets current annotation appearance state.

**Returns:**
java.lang.String
### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


Sets current annotation appearance state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getChecked() {#getChecked--}
```
public boolean getChecked()
```


Gets state of check box.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public void setChecked(boolean value)
```


Sets state of check box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNormalCaption() {#getNormalCaption--}
```
public String getNormalCaption()
```


Gets normal caption of the field.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public String getValue()
```


Gets value of check box field.

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets value of check box field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

