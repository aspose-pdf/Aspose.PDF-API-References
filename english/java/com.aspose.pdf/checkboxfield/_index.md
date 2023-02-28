---
title: CheckboxField
second_title: Aspose.PDF for Java API Reference
description: Class representing checkbox field
type: docs
weight: 58
url: /java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field)
```
public class CheckboxField extends Field
```

Class representing checkbox field
## Constructors

| Constructor | Description |
| --- | --- |
| [CheckboxField(Page page, Rectangle rect)](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for CheckboxField class. |
| [CheckboxField(IDocument doc, Rectangle rect)](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructor for CheckboxField class. |
| [CheckboxField()](#CheckboxField--) | Create instance of CheckboxField. |
| [CheckboxField(IDocument doc)](#CheckboxField-com.aspose.pdf.IDocument-) | Constructor to use with Generator. |
## Methods

| Method | Description |
| --- | --- |
| [getAllowedStates()](#getAllowedStates--) | Returns list of allowed states. |
| [getOnState()](#getOnState--) | Returns name of state which is "Checked" state of checkbox. |
| [getStyle()](#getStyle--) | Gets style of check box. |
| [setStyle(int value)](#setStyle-int-) | Sets style of check box. |
| [getActiveState()](#getActiveState--) | Gets current annotation appearance state. |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [getChecked()](#getChecked--) | Gets state of check box. |
| [setChecked(boolean value)](#setChecked-boolean-) | Sets state of check box. |
| [getNormalCaption()](#getNormalCaption--) | Gets normal caption of the field. |
| [getValue()](#getValue--) | Gets value of check box field. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets value of check box field. |
| [deepClone()](#deepClone--) | Clone the checkbox. |
| [getExportValue()](#getExportValue--) | Gets or sets export value of CheckBox field. |
| [setExportValue(String value)](#setExportValue-java.lang.String-) | Gets or sets export value of CheckBox field. |
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

### CheckboxField(IDocument doc, Rectangle rect) {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
```
public CheckboxField(IDocument doc, Rectangle rect)
```


Constructor for CheckboxField class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Document where will be new field created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where new field will be created. |

### CheckboxField() {#CheckboxField--}
```
public CheckboxField()
```


Create instance of CheckboxField.

### CheckboxField(IDocument doc) {#CheckboxField-com.aspose.pdf.IDocument-}
```
public CheckboxField(IDocument doc)
```


Constructor to use with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Document where field will be created. |

### getAllowedStates() {#getAllowedStates--}
```
public List<String> getAllowedStates()
```


Returns list of allowed states.

**Returns:**
java.util.List<java.lang.String> - list of String value
### getOnState() {#getOnState--}
```
public String getOnState()
```


Returns name of state which is "Checked" state of checkbox. This is "Yes" if presents or any other value other then "Off" and "No";

**Returns:**
java.lang.String - String value
### getStyle() {#getStyle--}
```
public int getStyle()
```


Gets style of check box.

**Returns:**
int - style of check box.
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Sets style of check box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | BoxStyle of check box. |

### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


Gets current annotation appearance state.

**Returns:**
java.lang.String - String value
### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


Sets current annotation appearance state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getChecked() {#getChecked--}
```
public boolean getChecked()
```


Gets state of check box.

**Returns:**
boolean - boolean value
### setChecked(boolean value) {#setChecked-boolean-}
```
public void setChecked(boolean value)
```


Sets state of check box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getNormalCaption() {#getNormalCaption--}
```
public String getNormalCaption()
```


Gets normal caption of the field.

**Returns:**
java.lang.String - String value
### getValue() {#getValue--}
```
public String getValue()
```


Gets value of check box field.

**Returns:**
java.lang.String - String value
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets value of check box field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the checkbox.

**Returns:**
java.lang.Object - The cloned object
### getExportValue() {#getExportValue--}
```
public final String getExportValue()
```


Gets or sets export value of CheckBox field.

**Returns:**
java.lang.String - String value
### setExportValue(String value) {#setExportValue-java.lang.String-}
```
public final void setExportValue(String value)
```


Gets or sets export value of CheckBox field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

