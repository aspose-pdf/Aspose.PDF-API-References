---
title: CheckboxField
linktitle: CheckboxField
second_title: Aspose.PDF for Java API Reference
description: Class representing checkbox field
type: docs
weight: 580
url: /java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Class representing checkbox field

## Constructors

| Constructor | Description |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc) |

## Methods

| Method | Description |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. The new checkbox is added to the bottom of the group. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. |
| [deepClone](#deepClone--) | Clone the checkbox. |
| [getActiveState](#getActiveState--) | Gets current annotation appearance state. |
| [getAllowedStates](#getAllowedStates--) | Returns list of allowed states. |
| [getChecked](#getChecked--) | Gets state of check box. |
| [getExportValue](#getExportValue--) | Gets or sets export value of CheckBox field. |
| [getNormalCaption](#getNormalCaption--) | Gets normal caption of the field. |
| [getOnState](#getOnState--) | Returns name of state which is "Checked" state of checkbox. This is "Yes" if presents or any other value other then "Off" and "No"; |
| [getStyle](#getStyle--) | Gets style of check box. |
| [getValue](#getValue--) | Gets value of check box field. |
| [setActiveState](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [setChecked](#setChecked-boolean-) | Sets state of check box. |
| [setExportValue](#setExportValue-java.lang.String-) | Gets or sets export value of CheckBox field. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Sets style of check box. |
| [setValue](#setValue-java.lang.String-) | Sets value of check box field. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Create instance of CheckboxField. @deprecated For full field functionality, a binding to the document is required - use CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time. The new checkbox is added to the bottom of the group.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Adds new checkbox into a checkbox group, in which at most one of the checkboxes may be checked at any time.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone the checkbox.

**Returns:**
The cloned object

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Gets current annotation appearance state.

**Returns:**
String value

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Returns list of allowed states.

**Returns:**
list of String value

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Gets state of check box.

**Returns:**
boolean value

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Gets or sets export value of CheckBox field.

**Returns:**
String value

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Gets normal caption of the field.

**Returns:**
String value

### getOnState {#getOnState--}
```
public String getOnState()
```

Returns name of state which is "Checked" state of checkbox. This is "Yes" if presents or any other value other then "Off" and "No";

**Returns:**
String value

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Gets style of check box.

**Returns:**
style of check box. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Gets value of check box field.

**Returns:**
String value

### setActiveState {#setActiveState-java.lang.String-}
Sets current annotation appearance state.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Sets state of check box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setExportValue {#setExportValue-java.lang.String-}
Gets or sets export value of CheckBox field.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Sets style of check box.

### setValue {#setValue-java.lang.String-}
Sets value of check box field.
