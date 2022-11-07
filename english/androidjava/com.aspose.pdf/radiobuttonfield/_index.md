---
title: RadioButtonField
second_title: Aspose.PDF for Java API Reference
description: Class representing radio button field.
type: docs
weight: 242
url: /java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field), [com.aspose.pdf.ChoiceField](../../com.aspose.pdf/choicefield)
```
public final class RadioButtonField extends ChoiceField
```

Class representing radio button field.
## Constructors

| Constructor | Description |
| --- | --- |
| [RadioButtonField(Page page, Rectangle rect)](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) |  |
| [RadioButtonField(Page page)](#RadioButtonField-com.aspose.pdf.Page-) | Constructor for RadiouttonField |
## Methods

| Method | Description |
| --- | --- |
| [getStyle()](#getStyle--) | Style of field box. |
| [setStyle(int value)](#setStyle-int-) |  |
| [getSelected()](#getSelected--) | Gets or sets index of selected item. |
| [setSelected(int value)](#setSelected-int-) |  |
| [getOptions()](#getOptions--) | Gets collection of options of the radio button. |
| [updateAppearances()](#updateAppearances--) |  |
| [add(RadioButtonOptionField newItem)](#add-com.aspose.pdf.RadioButtonOptionField-) | Adds new option field to RadioButton field |
| [addOption(String optionName, Rectangle rect)](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Add to radio button option with specifed rectangle. |
| [addOption(String optionName)](#addOption-java.lang.String-) | Add option to radion button. |
| [setPosition(Point point)](#setPosition-com.aspose.pdf.Point-) | Move all subitems of radio button to specified positins on the page. |
| [getPageIndex()](#getPageIndex--) | Gets index of page which contains this RadioButton field. |
| [getValue()](#getValue--) | Gets or sets value of field. |
| [setValue(String value)](#setValue-java.lang.String-) |  |
### RadioButtonField(Page page, Rectangle rect) {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public RadioButtonField(Page page, Rectangle rect)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### RadioButtonField(Page page) {#RadioButtonField-com.aspose.pdf.Page-}
```
public RadioButtonField(Page page)
```


Constructor for RadiouttonField

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |

### getStyle() {#getStyle--}
```
public int getStyle()
```


Style of field box.

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

### getSelected() {#getSelected--}
```
public int getSelected()
```


Gets or sets index of selected item. Numbering of items is started from 1.

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

### getOptions() {#getOptions--}
```
public OptionCollection getOptions()
```


Gets collection of options of the radio button.

**Returns:**
[OptionCollection](../../com.aspose.pdf/optioncollection)
### updateAppearances() {#updateAppearances--}
```
public void updateAppearances()
```




### add(RadioButtonOptionField newItem) {#add-com.aspose.pdf.RadioButtonOptionField-}
```
public void add(RadioButtonOptionField newItem)
```


Adds new option field to RadioButton field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newItem | [RadioButtonOptionField](../../com.aspose.pdf/radiobuttonoptionfield) |  |

### addOption(String optionName, Rectangle rect) {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
```
public void addOption(String optionName, Rectangle rect)
```


Add to radio button option with specifed rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| optionName | java.lang.String | Name of new option. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | New item rectangle. |

### addOption(String optionName) {#addOption-java.lang.String-}
```
public void addOption(String optionName)
```


Add option to radion button.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| optionName | java.lang.String |  |

### setPosition(Point point) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point point)
```


Move all subitems of radio button to specified positins on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) |  |

### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Gets index of page which contains this RadioButton field.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


Gets or sets value of field.

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

