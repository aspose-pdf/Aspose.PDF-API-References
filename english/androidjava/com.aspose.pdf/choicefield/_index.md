---
title: ChoiceField
second_title: Aspose.PDF for Java API Reference
description: Represents base class for choice fields.
type: docs
weight: 56
url: /java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field)
```
public abstract class ChoiceField extends Field
```

Represents base class for choice fields.
## Constructors

| Constructor | Description |
| --- | --- |
| [ChoiceField(Page page, Rectangle rect)](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for ChoiceField. |
## Methods

| Method | Description |
| --- | --- |
| [getCommitImmediately()](#getCommitImmediately--) | Gets commit on selection change flag. |
| [setCommitImmediately(boolean value)](#setCommitImmediately-boolean-) | Sets commit on selection change flag. |
| [getMultiSelect()](#getMultiSelect--) | Gets multiselection flag. |
| [setMultiSelect(boolean value)](#setMultiSelect-boolean-) | Sets multiselection flag. |
| [getSelected()](#getSelected--) | Gets index of selected option. |
| [setSelected(int value)](#setSelected-int-) | Sets index of selected option. |
| [getSelectedItems()](#getSelectedItems--) | Sets array of selected items. |
| [setSelectedItems(int[] value)](#setSelectedItems-int---) | Sets array of selected items. |
| [getOptions()](#getOptions--) | Gets collection of choice options. |
| [addOption(String optionName)](#addOption-java.lang.String-) | Adds new option with specified name. |
| [addOption(String export, String name)](#addOption-java.lang.String-java.lang.String-) | Adds new option with specified export value and name. |
| [deleteOption(String optionName)](#deleteOption-java.lang.String-) | Deletes option by its name. |
| [getValue()](#getValue--) | Gets value of the field. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets value of the field. |
### ChoiceField(Page page, Rectangle rect) {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public ChoiceField(Page page, Rectangle rect)
```


Constructor for ChoiceField.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getCommitImmediately() {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```


Gets commit on selection change flag.

**Returns:**
boolean
### setCommitImmediately(boolean value) {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```


Sets commit on selection change flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMultiSelect() {#getMultiSelect--}
```
public boolean getMultiSelect()
```


Gets multiselection flag.

**Returns:**
boolean
### setMultiSelect(boolean value) {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```


Sets multiselection flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSelected() {#getSelected--}
```
public int getSelected()
```


Gets index of selected option. This property allows to change selection.

**Returns:**
int
### setSelected(int value) {#setSelected-int-}
```
public void setSelected(int value)
```


Sets index of selected option. This property allows to change selection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSelectedItems() {#getSelectedItems--}
```
public int[] getSelectedItems()
```


Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item.

**Returns:**
int[]
### setSelectedItems(int[] value) {#setSelectedItems-int---}
```
public void setSelectedItems(int[] value)
```


Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getOptions() {#getOptions--}
```
public OptionCollection getOptions()
```


Gets collection of choice options.

**Returns:**
[OptionCollection](../../com.aspose.pdf/optioncollection)
### addOption(String optionName) {#addOption-java.lang.String-}
```
public void addOption(String optionName)
```


Adds new option with specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| optionName | java.lang.String | Name of the new option. |

### addOption(String export, String name) {#addOption-java.lang.String-java.lang.String-}
```
public void addOption(String export, String name)
```


Adds new option with specified export value and name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| export | java.lang.String | Export value. |
| name | java.lang.String | Name of the new option. |

### deleteOption(String optionName) {#deleteOption-java.lang.String-}
```
public void deleteOption(String optionName)
```


Deletes option by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| optionName | java.lang.String | Name of the option which must be deleted. |

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

