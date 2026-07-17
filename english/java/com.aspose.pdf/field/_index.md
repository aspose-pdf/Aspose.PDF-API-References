---
title: Field
linktitle: Field
second_title: Aspose.PDF for Java API Reference
description: Base class for acro form fields.
type: docs
weight: 1380
url: /java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Base class for acro form fields.

## Fields

| Field | Description |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Constructors

| Constructor | Description |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Creates field for use in Generator. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Copies subfields of this field into array starting from specified index. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copies subfields of this field into array starting from specified index. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Executes a specified JavaScript action for the field. |
| [flatten](#flatten--) | Removes this field and place its value directly on the page. |
| [get_Item](#get_Item-int-) | Gets subfield contained in this field by index. |
| [get_Item](#get_Item-java.lang.String-) | Gets subfield contained in this field by name of the subfield. |
| [getAlternateName](#getAlternateName--) | Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | Gets index of this anotation on the page. |
| [getMappingName](#getMappingName--) | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [getMaxFontSize](#getMaxFontSize--) | Maximal font size which can be used for field contents. -1 to don't check size. |
| [getMinFontSize](#getMinFontSize--) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [getPageIndex](#getPageIndex--) | Gets index of page which contains this field. |
| [getPartialName](#getPartialName--) | Gets partial name of the field. |
| [getRect](#getRect--) | Gets the field rectangle. |
| [getSyncRoot](#getSyncRoot--) | Synchronization object. |
| [getTabOrder](#getTabOrder--) | Gets or sets tab order of the field. |
| [getValue](#getValue--) | Gets value of the field. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | If true then font size will reduced to fit text to specified rectangle. |
| [isGroup](#isGroup--) | Gets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [isSynchronized](#isSynchronized--) | Returns true if dictionary is synchronized. |
| [iterator](#iterator--) | Returns enumerator of contained fields. |
| [recalculate](#recalculate--) | Recaculates all calculated fields on the form. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Sets index of this anotation on the page. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | If true then font size will reduced to fit text to specified rectangle. |
| [setMappingName](#setMappingName-java.lang.String-) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [setMaxFontSize](#setMaxFontSize-double-) | Maximal font size which can be used for field contents. -1 to don't check size. |
| [setMinFontSize](#setMinFontSize-double-) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [setPartialName](#setPartialName-java.lang.String-) | Sets partial name of the field. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Set position of the field. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Sets the field rectangle. |
| [setSharedField](#setSharedField-boolean-) | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page. |
| [setTabOrder](#setTabOrder-int-) | Gets or sets tab order of the field. |
| [setValue](#setValue-java.lang.String-) | Set value. |
| [size](#size--) | Gets number of subfields in this field. (For example number of items in radio button field). |
| [updateAppearances](#updateAppearances--) | Update appearances value. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Creates field for use in Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Copies subfields of this field into array starting from specified index.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copies subfields of this field into array starting from specified index.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Executes a specified JavaScript action for the field.

### flatten {#flatten--}
```
public void flatten()
```

Removes this field and place its value directly on the page.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Gets subfield contained in this field by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of the reuqested subfield. |

**Returns:**
Field instance.

### get_Item {#get_Item-java.lang.String-}
Gets subfield contained in this field by name of the subfield.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat.

**Returns:**
String value

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Gets index of this anotation on the page.

**Returns:**
int value

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Gets mapping name of the field that shall be used when exporting interactive form field data from the document.

**Returns:**
String value

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Maximal font size which can be used for field contents. -1 to don't check size.

**Returns:**
double value

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Minimal font size which can be used for field contents. -1 to don't check size.

**Returns:**
double value

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Gets index of page which contains this field.

**Returns:**
int value

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Gets partial name of the field.

**Returns:**
String value

### getRect {#getRect--}
```
public Rectangle getRect()
```

Gets the field rectangle.

**Returns:**
the field rectangle.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Synchronization object.

**Returns:**
object value

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Gets or sets tab order of the field.

**Returns:**
int value

### getValue {#getValue--}
```
public String getValue()
```

Gets value of the field.

**Returns:**
String value

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

If true then font size will reduced to fit text to specified rectangle.

**Returns:**
boolean value

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Gets boolean value which indicates is this field non-terminal field i.e. group of fields.

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returns true if dictionary is synchronized.

**Returns:**
boolean value

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Returns enumerator of contained fields.

**Returns:**
Enumerator object.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Recaculates all calculated fields on the form.

**Returns:**
true if field value was changed during recalculation.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Sets index of this anotation on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

If true then font size will reduced to fit text to specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMappingName {#setMappingName-java.lang.String-}
Sets mapping name of the field that shall be used when exporting interactive form field data from the document.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Maximal font size which can be used for field contents. -1 to don't check size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Minimal font size which can be used for field contents. -1 to don't check size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setPartialName {#setPartialName-java.lang.String-}
Sets partial name of the field.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Set position of the field.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Sets the field rectangle.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Gets or sets tab order of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setValue {#setValue-java.lang.String-}
Set value.

### size {#size--}
```
public int size()
```

Gets number of subfields in this field. (For example number of items in radio button field).

**Returns:**
int value

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Update appearances value.
