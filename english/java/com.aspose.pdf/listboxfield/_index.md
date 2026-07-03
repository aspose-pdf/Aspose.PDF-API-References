---
title: ListBoxField
second_title: Aspose.PDF for Java API Reference
description: Class represents ListBox field.
type: docs
weight: 2770
url: /java/com.aspose.pdf/listboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.ChoiceField, com.aspose.pdf.ListBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class ListBoxField extends ChoiceField
```

Class represents ListBox field.

## Constructors

| Constructor | Description |
| --- | --- |
| [ListBoxField](#ListBoxField--) | Constructor for ListBoxField to be used in Generator. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructor for ListBoxField to be used in Generator. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor for ListBoxField to be used in Generator. |

## Methods

| Method | Description |
| --- | --- |
| [getTopIndex](#getTopIndex--) | Gets index of the top visible element of the list. |
| [setSelected](#setSelected-int-) | Gets index of the selected item. Items are numbered from 1. |
| [setSelectedItems](#setSelectedItems-int:A-) | Sets array of the selected items in the multiselect list. For single-select list returns array with single item. |
| [setTopIndex](#setTopIndex-int-) | Sets index of the top visible element of the list. |

### ListBoxField {#ListBoxField--}
```
public ListBoxField()
```

Constructor for ListBoxField to be used in Generator.

### ListBoxField {#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Constructor for ListBoxField to be used in Generator.

### ListBoxField {#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructor for ListBoxField to be used in Generator.

### getTopIndex {#getTopIndex--}
```
public int getTopIndex()
```

Gets index of the top visible element of the list.

**Returns:**
int value

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Gets index of the selected item. Items are numbered from 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Sets array of the selected items in the multiselect list. For single-select list returns array with single item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | array of int values |

### setTopIndex {#setTopIndex-int-}
```
public void setTopIndex(int value)
```

Sets index of the top visible element of the list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
