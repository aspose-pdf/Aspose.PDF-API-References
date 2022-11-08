---
title: TableTRElement
second_title: Aspose.PDF for Java API Reference
description: Represents TR structure element in logical structure of the table.
type: docs
weight: 28
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)
```
public final class TableTRElement extends TableChildElement
```

Represents TR structure element in logical structure of the table.
## Constructors

| Constructor | Description |
| --- | --- |
| [TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor for internal usage only |
## Methods

| Method | Description |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Find Elements of a given type |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Find Elements of a given type |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Append  /Aspose.Pdf.LogicalStructure.Element  to collection of children. |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Change parent element for current structure element |
| [clearId()](#clearId--) | Clear ID for structure element. |
| [createTD()](#createTD--) | Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table. |
| [createTH()](#createTH--) | Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | Generate ID for structure element. |
| [getActualText()](#getActualText--) | Gets or sets the actual text for structure element. |
| [getAlternativeText()](#getAlternativeText--) | Gets or sets the alternative text for structure element. |
| [getAttributes()](#getAttributes--) | Gets  StructureAttributeCollection  object. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the row background color. |
| [getBorder()](#getBorder--) | Gets or sets the row border. |
| [getChildElements()](#getChildElements--) | Gets children collection of  Element  objects. |
| [getClass()](#getClass--) |  |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object. |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border. |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets or sets default margin for row cells. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets or sets default text state for row cells |
| [getElementEngine()](#getElementEngine--) | Get parent element. |
| [getExpansionText()](#getExpansionText--) | Gets or sets the expansion text for structure element. |
| [getFixedRowHeight()](#getFixedRowHeight--) | Gets fixed row height - row may have fixed height. |
| [getID()](#getID--) | Gets the ID for structure element. |
| [getLanguage()](#getLanguage--) | Gets or sets the language for structure element. |
| [getMinRowHeight()](#getMinRowHeight--) | Gets height for row. |
| [getParentElement()](#getParentElement--) | Gets parent collection of  Element  objects. |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | Gets type of structure element. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | Gets or sets the title for structure element. |
| [getTrailer()](#getTrailer--) | Internam method |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets or sets the vertical alignment. |
| [hashCode()](#hashCode--) |  |
| [isInNewPage()](#isInNewPage--) | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [isRowBroken()](#isRowBroken--) | Gets is row can be broken between two pages. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Gets or sets the actual text for structure element. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gets or sets the alternative text for structure element. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the row background color. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the row border. |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Gets or sets default margin for row cells. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets default text state for row cells |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Gets or sets the expansion text for structure element. |
| [setFixedRowHeight(double value)](#setFixedRowHeight-double-) | Gets fixed row height - row may have fixed height. |
| [setId(String id)](#setId-java.lang.String-) | Sets ID for structure element. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Gets or sets the language for structure element. |
| [setMinRowHeight(double value)](#setMinRowHeight-double-) | Gets height for row. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | set Parent Element |
| [setRowBroken(boolean value)](#setRowBroken-boolean-) | Gets is row can be broken between two pages. |
| [setTag(String newTag)](#setTag-java.lang.String-) | Sets custom tag for structure element. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets the title for structure element. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Gets or sets the vertical alignment. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
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

### createTD() {#createTD--}
```
public final TableTDElement createTD()
```


Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table.

**Returns:**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - Created structure element.
### createTH() {#createTH--}
```
public final TableTHElement createTH()
```


Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table.

**Returns:**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - Created structure element.
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


Gets or sets the row background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color instance
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets or sets the row border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
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


Gets or sets default margin for row cells.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo instance
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Gets or sets default text state for row cells

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
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
### getFixedRowHeight() {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```


Gets fixed row height - row may have fixed height.

**Returns:**
double - double value
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
### getMinRowHeight() {#getMinRowHeight--}
```
public final double getMinRowHeight()
```


Gets height for row.

**Returns:**
double - double value
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Gets parent collection of  Element  objects.

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Value: Parent collection of  Element  objects.
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
### getTrailer() {#getTrailer--}
```
public final ITrailerable getTrailer()
```


Internam method

**Returns:**
[ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) - Internal element
### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Gets or sets the vertical alignment.

**Returns:**
int - VerticalAlignment element
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInNewPage() {#isInNewPage--}
```
public final boolean isInNewPage()
```


Gets fixed row is in new page - page with this property should be printed to next page Default false.

**Returns:**
boolean - boolean value
### isRowBroken() {#isRowBroken--}
```
public final boolean isRowBroken()
```


Gets is row can be broken between two pages.

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


Gets or sets the row background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color instance |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Gets or sets the row border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

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


Gets or sets default margin for row cells.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo instance |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Gets or sets default text state for row cells

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### setExpansionText(String value) {#setExpansionText-java.lang.String-}
```
public final void setExpansionText(String value)
```


Gets or sets the expansion text for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Expansion text of the structure element. |

### setFixedRowHeight(double value) {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```


Gets fixed row height - row may have fixed height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setId(String id) {#setId-java.lang.String-}
```
public final void setId(String id)
```


Sets ID for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | ID value for structure element |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```


Gets fixed row is in new page - page with this property should be printed to next page Default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Gets or sets the language for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Language of the structure element. |

### setMinRowHeight(double value) {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```


Gets height for row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


set Parent Element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | value |

### setRowBroken(boolean value) {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```


Gets is row can be broken between two pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Gets or sets the vertical alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

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

