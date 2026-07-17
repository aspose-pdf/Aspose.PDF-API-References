---
title: RadioButtonField
linktitle: RadioButtonField
second_title: Aspose.PDF for Java API Reference
description: Class representing radio button field.
type: docs
weight: 4080
url: /java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Class representing radio button field.

## Constructors

| Constructor | Description |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Constructor for RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Constructor for RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Sets radio button field |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Adds new option field to RadioButton field |
| [addOption](#addOption-java.lang.String-) | Add option to radion button. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Add to radio button option with specifed rectangle. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Get or sets the flag that allows the radiobutton to have no selected value. If {@code }, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If {@code }, clicking the selected button deselects it, leaving no button selected. </p> <hr> Some PDF readers (including Adobe Acrobat) may ignore the state of the flag. |
| [getOptions](#getOptions--) | Gets collection of options of the radio button. |
| [getPageIndex](#getPageIndex--) | Gets index of page which contains this RadioButton field. |
| [getSelected](#getSelected--) | Gets index of selected item. Numbering of items is started from 1. |
| [getStyle](#getStyle--) | Style of field box. |
| [getValue](#getValue--) | Gets value of field. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Get or sets the flag that allows the radiobutton to have no selected value. If {@code }, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If {@code }, clicking the selected button deselects it, leaving no button selected. </p> <hr> Some PDF readers (including Adobe Acrobat) may ignore the state of the flag. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Move all subitems of radio button to specified positins on the page. |
| [setSelected](#setSelected-int-) | Sets index of selected item. Numbering of items is started from 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Style of field box. |
| [setValue](#setValue-java.lang.String-) | Sets value of field. |
| [updateAppearances](#updateAppearances--) | Update appearances value. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Constructor for RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Constructor for RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Sets radio button field

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Adds new option field to RadioButton field

### addOption {#addOption-java.lang.String-}
Add option to radion button.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Add to radio button option with specifed rectangle.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Get or sets the flag that allows the radiobutton to have no selected value. If {@code }, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If {@code }, clicking the selected button deselects it, leaving no button selected. </p> <hr> Some PDF readers (including Adobe Acrobat) may ignore the state of the flag.

**Returns:**
boolean value

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Gets collection of options of the radio button.

**Returns:**
OptionCollection object

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Gets index of page which contains this RadioButton field.

**Returns:**
int value

### getSelected {#getSelected--}
```
public int getSelected()
```

Gets index of selected item. Numbering of items is started from 1.

**Returns:**
int value

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Style of field box.

**Returns:**
BoxStyle value @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Gets value of field.

**Returns:**
String value

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Get or sets the flag that allows the radiobutton to have no selected value. If {@code }, exactly one radio button shall be selected at all times; selecting the currently selected button has no effect. If {@code }, clicking the selected button deselects it, leaving no button selected. </p> <hr> Some PDF readers (including Adobe Acrobat) may ignore the state of the flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Move all subitems of radio button to specified positins on the page.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Sets index of selected item. Numbering of items is started from 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Style of field box.

### setValue {#setValue-java.lang.String-}
Sets value of field.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Update appearances value.
