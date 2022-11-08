---
title: TableElement
second_title: Aspose.PDF for Java API Reference
description: Represents Table structure element in logical structure.
type: docs
weight: 21
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/blselement)
```
public final class TableElement extends BLSElement
```

Represents Table structure element in logical structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor for internal usage only |
## Methods

| Method | Description |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Find Elements of a given type |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Find Elements of a given type |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Append  /Aspose.Pdf.LogicalStructure.Element  to collection of children. |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Change parent element for current structure element |
| [clearId()](#clearId--) | Clear ID for structure element. |
| [createTBody()](#createTBody--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table. |
| [createTFoot()](#createTFoot--) | Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) and added it to current table. |
| [createTHead()](#createTHead--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | Generate ID for structure element. |
| [getActualText()](#getActualText--) | Gets or sets the actual text for structure element. |
| [getAlignment()](#getAlignment--) | Gets or sets the table alignment. |
| [getAlternativeText()](#getAlternativeText--) | Gets or sets the alternative text for structure element. |
| [getAttributes()](#getAttributes--) | Gets  StructureAttributeCollection  object. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the table background color. |
| [getBorder()](#getBorder--) | Gets or sets the table border. |
| [getBroken()](#getBroken--) | Gets or sets table vertical broken; |
| [getChildElements()](#getChildElements--) | Gets children collection of  Element  objects. |
| [getClass()](#getClass--) |  |
| [getColumnAdjustment()](#getColumnAdjustment--) | Gets or sets the table column adjustment. |
| [getColumnWidths()](#getColumnWidths--) | Gets the column widths of the table. |
| [getCornerStyle()](#getCornerStyle--) | Gets or sets the styles of the border corners |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object. |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border. |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets or sets the default cell padding. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets or sets the default cell text state. |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | Gets or sets default column width. |
| [getElementEngine()](#getElementEngine--) | Get parent element. |
| [getExpansionText()](#getExpansionText--) | Gets or sets the expansion text for structure element. |
| [getID()](#getID--) | Gets the ID for structure element. |
| [getLanguage()](#getLanguage--) | Gets or sets the language for structure element. |
| [getLeft()](#getLeft--) | Gets or sets the table left coordinate. |
| [getParentElement()](#getParentElement--) | Gets parent collection of  Element  objects. |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | Gets or sets the maximum columns count for table. |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | Gets the first rows count repeated for several pages. |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | Gets the style for repeating rows. |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | Gets type of structure element. |
| [getTable()](#getTable--) |  |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | Gets or sets the title for structure element. |
| [getTop()](#getTop--) | Gets or sets the table top coordinate. |
| [getTrailer()](#getTrailer--) | Internam method |
| [hashCode()](#hashCode--) |  |
| [isBordersIncluded()](#isBordersIncluded--) | Gets or sets border included in column widhts. |
| [isBroken()](#isBroken--) | Gets or sets the table is broken - will be truncated for next page. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Gets or sets the actual text for structure element. |
| [setAlignment(int value)](#setAlignment-int-) | Gets or sets the table alignment. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gets or sets the alternative text for structure element. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the table background color. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the table border. |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | Gets or sets border included in column widhts. |
| [setBroken(boolean value)](#setBroken-boolean-) | Gets or sets the table is broken - will be truncated for next page. |
| [setBroken(int value)](#setBroken-int-) | Gets or sets table vertical broken; |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | Gets or sets the table column adjustment. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Gets the column widths of the table. |
| [setCornerStyle(int value)](#setCornerStyle-int-) | Gets or sets the styles of the border corners |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Gets or sets the default cell padding. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets the default cell text state. |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | Gets or sets default column width. |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Gets or sets the expansion text for structure element. |
| [setId(String id)](#setId-java.lang.String-) | Sets ID for structure element. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Gets or sets the language for structure element. |
| [setLeft(float value)](#setLeft-float-) | Gets or sets the table left coordinate. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | set Parent Element |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | Gets or sets the maximum columns count for table. |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | Gets the first rows count repeated for several pages. |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Gets the style for repeating rows. |
| [setTag(String newTag)](#setTag-java.lang.String-) | Sets custom tag for structure element. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets the title for structure element. |
| [setTop(float value)](#setTop-float-) | Gets or sets the table top coordinate. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


constructor for internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) | TaggedContext instance |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | internal instance |

### <T>findElements(Class<T> typeOfTboolean) {#-T-findElements-java.lang.Class-T--}
```
public List<T> <T>findElements(Class<T> typeOfTboolean)
```


Find Elements of a given type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfTboolean | java.lang.Class<T> | class instance |

**Returns:**
java.util.List<T> - List of found Elements
### <T>findElements(Class<T> typeOfT, boolean recursiveSearch) {#-T-findElements-java.lang.Class-T--boolean-}
```
public List<T> <T>findElements(Class<T> typeOfT, boolean recursiveSearch)
```


Find Elements of a given type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> | class instance |
| recursiveSearch | boolean | (Optional) Recursive Search (default false, search only from direct children) |

**Returns:**
java.util.List<T> - List of found Elements
### appendChild(Element element) {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public final Element appendChild(Element element)
```


Append  /Aspose.Pdf.LogicalStructure.Element  to collection of children.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  /Aspose.Pdf.LogicalStructure.Element  object to add. |

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) -  /Aspose.Pdf.LogicalStructure.Element  which has been added.
### changeParentElement(StructureElement newParentElement) {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public final void changeParentElement(StructureElement newParentElement)
```


Change parent element for current structure element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newParentElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) | New parent structure element |

### clearId() {#clearId--}
```
public final void clearId()
```


Clear ID for structure element.

### createTBody() {#createTBody--}
```
public final TableTBodyElement createTBody()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table.

**Returns:**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - Created structure element.
### createTFoot() {#createTFoot--}
```
public final TableTFootElement createTFoot()
```


Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) and added it to current table.

**Returns:**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - Created structure element.
### createTHead() {#createTHead--}
```
public final TableTHeadElement createTHead()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table.

**Returns:**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - Created structure element.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateId() {#generateId--}
```
public final void generateId()
```


Generate ID for structure element.

### getActualText() {#getActualText--}
```
public final String getActualText()
```


Gets or sets the actual text for structure element.

**Returns:**
java.lang.String - Value: Actual text of the structure element.
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Gets or sets the table alignment.

**Returns:**
int - HorizontalAlignment element
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets or sets the alternative text for structure element.

**Returns:**
java.lang.String - Value: Alternative text of the structure element.
### getAttributes() {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```


Gets  StructureAttributeCollection  object.

**Returns:**
[StructureAttributeCollection](../../com.aspose.pdf.tagged.logicalstructure/structureattributecollection) -  StructureAttributeCollection  object.
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets or sets the table background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color instance
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets or sets the table border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### getBroken() {#getBroken--}
```
public final int getBroken()
```


Gets or sets table vertical broken;

**Returns:**
int - TableBroken element
### getChildElements() {#getChildElements--}
```
public final ElementList getChildElements()
```


Gets children collection of  Element  objects.

**Returns:**
[ElementList](../../com.aspose.pdf.tagged.logicalstructure/elementlist) - Value: Children collection of  Element  objects.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


Gets or sets the table column adjustment.

**Returns:**
int - ColumnAdjustment element
### getColumnWidths() {#getColumnWidths--}
```
public final String getColumnWidths()
```


Gets the column widths of the table.

**Returns:**
java.lang.String - String value
### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


Gets or sets the styles of the border corners

**Returns:**
int - BorderCornerStyle element
### getDefaultAttributeOwner() {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```


Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object.

Value:  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object.

**Returns:**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - AttributeOwnerStandard instance
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


Gets default cell border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


Gets or sets the default cell padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo instance
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Gets or sets the default cell text state.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


Gets or sets default column width.

**Returns:**
java.lang.String - String value
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


Get parent element.

**Returns:**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - Value: Parent element.
### getExpansionText() {#getExpansionText--}
```
public final String getExpansionText()
```


Gets or sets the expansion text for structure element.

**Returns:**
java.lang.String - Value: Expansion text of the structure element.
### getID() {#getID--}
```
public final String getID()
```


Gets the ID for structure element.

Value: ID of the structure element.

**Returns:**
java.lang.String - String value
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets or sets the language for structure element.

**Returns:**
java.lang.String - Value: Language of the structure element.
### getLeft() {#getLeft--}
```
public final float getLeft()
```


Gets or sets the table left coordinate.

**Returns:**
float - float value
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Gets parent collection of  Element  objects.

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Value: Parent collection of  Element  objects.
### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


Gets or sets the maximum columns count for table.

**Returns:**
int - int value
### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


Gets the first rows count repeated for several pages.

**Returns:**
int - int value
### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


Gets the style for repeating rows.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
### getS() {#getS--}
```
public final IPdfName getS()
```




**Returns:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
### getStructureType() {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```


Gets type of structure element.

**Returns:**
[StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard) - Value:  StructureTypeStandard  object of structure element.
### getTable() {#getTable--}
```
public final Table getTable()
```




**Returns:**
[Table](../../com.aspose.pdf/table)
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```




**Returns:**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent)
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets or sets the title for structure element.

**Returns:**
java.lang.String - Value: Title of the structure element.
### getTop() {#getTop--}
```
public final float getTop()
```


Gets or sets the table top coordinate.

**Returns:**
float - float value
### getTrailer() {#getTrailer--}
```
public final ITrailerable getTrailer()
```


Internam method

**Returns:**
[ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) - Internal element
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


Gets or sets border included in column widhts.

**Returns:**
boolean - boolean value
### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


Gets or sets the table is broken - will be truncated for next page.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setActualText(String value) {#setActualText-java.lang.String-}
```
public final void setActualText(String value)
```


Gets or sets the actual text for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Actual text of the structure element. |

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Gets or sets the table alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment element |

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Gets or sets the alternative text for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Alternative text of the structure element. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Gets or sets the table background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color instance |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Gets or sets the table border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


Gets or sets border included in column widhts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


Gets or sets the table is broken - will be truncated for next page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


Gets or sets table vertical broken;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TableBroken element |

### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


Gets or sets the table column adjustment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColumnAdjustment element |

### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public final void setColumnWidths(String value)
```


Gets the column widths of the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


Gets or sets the styles of the border corners

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | BorderCornerStyle element |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


Gets default cell border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


Gets or sets the default cell padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo instance |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Gets or sets the default cell text state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


Gets or sets default column width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setExpansionText(String value) {#setExpansionText-java.lang.String-}
```
public final void setExpansionText(String value)
```


Gets or sets the expansion text for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Expansion text of the structure element. |

### setId(String id) {#setId-java.lang.String-}
```
public final void setId(String id)
```


Sets ID for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | ID value for structure element |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Gets or sets the language for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Language of the structure element. |

### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


Gets or sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


set Parent Element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | value |

### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


Gets or sets the maximum columns count for table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


Gets the first rows count repeated for several pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


Gets the style for repeating rows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### setTag(String newTag) {#setTag-java.lang.String-}
```
public final void setTag(String newTag)
```


Sets custom tag for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newTag | java.lang.String | Tag name |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Gets or sets the title for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Title of the structure element. |

### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


Gets or sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - String that represents the current object.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

