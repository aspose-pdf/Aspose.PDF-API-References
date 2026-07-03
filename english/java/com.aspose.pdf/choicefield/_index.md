---
title: ChoiceField
second_title: Aspose.PDF for Java API Reference
description: Represents base class for choice fields.
type: docs
weight: 590
url: /java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Represents base class for choice fields.

## Constructors

| Constructor | Description |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Creates choice field (for Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructor for ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for ChoiceField. |

## Methods

| Method | Description |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Adds new option with specified name. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Adds new option with specified export value and name. |
| [deleteOption](#deleteOption-java.lang.String-) | Deletes option by its name. |
| [getCommitImmediately](#getCommitImmediately--) | Gets commit on selection change flag. |
| [getMultiSelect](#getMultiSelect--) | Gets multiselection flag. |
| [getOptions](#getOptions--) | Gets collection of choice options. |
| [getSelected](#getSelected--) | Gets index of selected option. This property allows to change selection. |
| [getSelectedItems](#getSelectedItems--) | Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [getValue](#getValue--) | Gets value of the field. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Sets commit on selection change flag. |
| [setMultiSelect](#setMultiSelect-boolean-) | Sets multiselection flag. |
| [setOptions](#setOptions-java.util.List-) | Replaces the available options with those whose names are given in the options parameter. |
| [setSelected](#setSelected-int-) | Sets index of selected option. This property allows to change selection. |
| [setSelectedItems](#setSelectedItems-int:A-) | Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item. |
| [setValue](#setValue-java.lang.String-) | Sets value of the field. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Creates choice field (for Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Constructor for ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructor for ChoiceField.

### addOption {#addOption-java.lang.String-}
Adds new option with specified name.

### addOption {#addOption-java.lang.String-java.lang.String-}
Adds new option with specified export value and name.

### deleteOption {#deleteOption-java.lang.String-}
Deletes option by its name.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Gets commit on selection change flag.

**Returns:**
boolean value

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Gets multiselection flag.

**Returns:**
boolean value

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Gets collection of choice options.

**Returns:**
OptionCollection object

### getSelected {#getSelected--}
```
public int getSelected()
```

Gets index of selected option. This property allows to change selection.

**Returns:**
int value

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item.

**Returns:**
array of int values

### getValue {#getValue--}
```
public String getValue()
```

Gets value of the field.

**Returns:**
String value

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Sets commit on selection change flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Sets multiselection flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOptions {#setOptions-java.util.List-}
Replaces the available options with those whose names are given in the options parameter.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Sets index of selected option. This property allows to change selection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | array of int values |

### setValue {#setValue-java.lang.String-}
Sets value of the field.
