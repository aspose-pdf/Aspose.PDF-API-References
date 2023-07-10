---
title: ChoiceField
second_title: Aspose.PDF for Java API Reference
description: Represents base class for choice fields.
type: docs
weight: 59
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
| [ChoiceField(IDocument doc)](#ChoiceField-com.aspose.pdf.IDocument-) | Creates choice field (for Generator) |
| [ChoiceField(IDocument doc, Rectangle rect)](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructor for ChoiceField. |
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
| [setOptions(List<String> options)](#setOptions-java.util.List-java.lang.String--) | Replaces the available options with those whose names are given in the options parameter. |
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
| page | [Page](../../com.aspose.pdf/page) | Page where field is situated. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle of the field. |

### ChoiceField(IDocument doc) {#ChoiceField-com.aspose.pdf.IDocument-}
```
public ChoiceField(IDocument doc)
```


Creates choice field (for Generator)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Document where choice field will be created. |

### ChoiceField(IDocument doc, Rectangle rect) {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
```
public ChoiceField(IDocument doc, Rectangle rect)
```


Constructor for ChoiceField.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Document where field will be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle of the field. |

### getCommitImmediately() {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```


Gets commit on selection change flag.

**Returns:**
boolean - boolean value
### setCommitImmediately(boolean value) {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```


Sets commit on selection change flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMultiSelect() {#getMultiSelect--}
```
public boolean getMultiSelect()
```


Gets multiselection flag.

**Returns:**
boolean - boolean value
### setMultiSelect(boolean value) {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```


Sets multiselection flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSelected() {#getSelected--}
```
public int getSelected()
```


Gets index of selected option. This property allows to change selection.

**Returns:**
int - int value
### setSelected(int value) {#setSelected-int-}
```
public void setSelected(int value)
```


Sets index of selected option. This property allows to change selection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getSelectedItems() {#getSelectedItems--}
```
public int[] getSelectedItems()
```


Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item.

**Returns:**
int[] - array of int values
### setSelectedItems(int[] value) {#setSelectedItems-int---}
```
public void setSelectedItems(int[] value)
```


Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | array of int values |

### getOptions() {#getOptions--}
```
public OptionCollection getOptions()
```


Gets collection of choice options.

**Returns:**
[OptionCollection](../../com.aspose.pdf/optioncollection) - OptionCollection object
### setOptions(List<String> options) {#setOptions-java.util.List-java.lang.String--}
```
public final void setOptions(List<String> options)
```


Replaces the available options with those whose names are given in the options parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | java.util.List<java.lang.String> | List of names for new options. |

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
java.lang.String - String value
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets value of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

