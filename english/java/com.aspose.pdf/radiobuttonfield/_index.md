---
title: RadioButtonField
second_title: Aspose.PDF for Java API Reference
description: Class representing radio button field.
type: docs
weight: 299
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
| [RadioButtonField(Page page, Rectangle rect)](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Sets radio button field |
| [RadioButtonField(Page page)](#RadioButtonField-com.aspose.pdf.Page-) | Constructor for RadiouttonField |
| [RadioButtonField(IDocument doc)](#RadioButtonField-com.aspose.pdf.IDocument-) | Constructor for RadioButtonField. |
## Methods

| Method | Description |
| --- | --- |
| [getStyle()](#getStyle--) | Style of field box. |
| [setStyle(int value)](#setStyle-int-) | Style of field box. |
| [getSelected()](#getSelected--) | Gets index of selected item. |
| [setSelected(int value)](#setSelected-int-) | Sets index of selected item. |
| [getOptions()](#getOptions--) | Gets collection of options of the radio button. |
| [updateAppearances()](#updateAppearances--) | Update appearances value. |
| [add(RadioButtonOptionField newItem)](#add-com.aspose.pdf.RadioButtonOptionField-) | Adds new option field to RadioButton field |
| [addOption(String optionName, Rectangle rect)](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Add to radio button option with specifed rectangle. |
| [addOption(String optionName)](#addOption-java.lang.String-) | Add option to radion button. |
| [setPosition(Point point)](#setPosition-com.aspose.pdf.Point-) | Move all subitems of radio button to specified positins on the page. |
| [getPageIndex()](#getPageIndex--) | Gets index of page which contains this RadioButton field. |
| [getValue()](#getValue--) | Gets value of field. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets value of field. |
### RadioButtonField(Page page, Rectangle rect) {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public RadioButtonField(Page page, Rectangle rect)
```


Sets radio button field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### RadioButtonField(Page page) {#RadioButtonField-com.aspose.pdf.Page-}
```
public RadioButtonField(Page page)
```


Constructor for RadiouttonField

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where radio button will be placed. |

### RadioButtonField(IDocument doc) {#RadioButtonField-com.aspose.pdf.IDocument-}
```
public RadioButtonField(IDocument doc)
```


Constructor for RadioButtonField.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Document where radio button will be created. |

### getStyle() {#getStyle--}
```
public int getStyle()
```


Style of field box.

**Returns:**
int - BoxStyle value
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Style of field box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | BoxStyle value |

### getSelected() {#getSelected--}
```
public int getSelected()
```


Gets index of selected item. Numbering of items is started from 1.

**Returns:**
int - int value
### setSelected(int value) {#setSelected-int-}
```
public void setSelected(int value)
```


Sets index of selected item. Numbering of items is started from 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getOptions() {#getOptions--}
```
public OptionCollection getOptions()
```


Gets collection of options of the radio button.

**Returns:**
[OptionCollection](../../com.aspose.pdf/optioncollection) - OptionCollection object
### updateAppearances() {#updateAppearances--}
```
public void updateAppearances()
```


Update appearances value.

### add(RadioButtonOptionField newItem) {#add-com.aspose.pdf.RadioButtonOptionField-}
```
public void add(RadioButtonOptionField newItem)
```


Adds new option field to RadioButton field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newItem | [RadioButtonOptionField](../../com.aspose.pdf/radiobuttonoptionfield) | Item which should be added. |

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
| optionName | java.lang.String | Name of the option which will be added. |

### setPosition(Point point) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point point)
```


Move all subitems of radio button to specified positins on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | Sets position of RadioButton field annotations. |

### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Gets index of page which contains this RadioButton field.

**Returns:**
int - int value
### getValue() {#getValue--}
```
public String getValue()
```


Gets value of field.

**Returns:**
java.lang.String - String value
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets value of field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

