---
title: ListBoxField
second_title: Aspose.PDF for Java API Reference
description: Class represents ListBox field.
type: docs
weight: 167
url: /java/com.aspose.pdf/listboxfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field), [com.aspose.pdf.ChoiceField](../../com.aspose.pdf/choicefield)
```
public final class ListBoxField extends ChoiceField
```

Class represents ListBox field.
## Constructors

| Constructor | Description |
| --- | --- |
| [ListBoxField()](#ListBoxField--) | Constructor for ListBoxField to be used in Generator. |
| [ListBoxField(Page page, Rectangle rect)](#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new ListBox field. |
## Methods

| Method | Description |
| --- | --- |
| [getTopIndex()](#getTopIndex--) | Gets index of the top visible element of the list. |
| [setTopIndex(int value)](#setTopIndex-int-) | Sets index of the top visible element of the list. |
| [setSelected(int value)](#setSelected-int-) | Gets index of the selected item. |
| [setSelectedItems(int[] value)](#setSelectedItems-int---) | Gets array of the selected items in the multiselect list. |
### ListBoxField() {#ListBoxField--}
```
public ListBoxField()
```


Constructor for ListBoxField to be used in Generator.

### ListBoxField(Page page, Rectangle rect) {#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public ListBoxField(Page page, Rectangle rect)
```


Creates new ListBox field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where list box will be placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where list box will be placed on the page. |

### getTopIndex() {#getTopIndex--}
```
public int getTopIndex()
```


Gets index of the top visible element of the list.

**Returns:**
int
### setTopIndex(int value) {#setTopIndex-int-}
```
public void setTopIndex(int value)
```


Sets index of the top visible element of the list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSelected(int value) {#setSelected-int-}
```
public void setSelected(int value)
```


Gets index of the selected item. Items are numbered from 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSelectedItems(int[] value) {#setSelectedItems-int---}
```
public void setSelectedItems(int[] value)
```


Gets array of the selected items in the multiselect list. For single-select list returns array with single item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

