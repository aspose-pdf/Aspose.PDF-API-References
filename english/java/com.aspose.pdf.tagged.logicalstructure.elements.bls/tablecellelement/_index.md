---
title: TableCellElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for table cell elements TH and TD in logical structure.
type: docs
weight: 19
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)

**All Implemented Interfaces:**
[com.aspose.pdf.tagged.logicalstructure.elements.ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement)
```
public abstract class TableCellElement extends TableChildElement implements ITextElement
```

Represents a base class for table cell elements (TH and TD) in logical structure.
## Methods

| Method | Description |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Find Elements of a given type |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Find Elements of a given type |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Append  /Aspose.Pdf.LogicalStructure.Element  to collection of children. |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Change parent element for current structure element |
| [clearId()](#clearId--) | Clear ID for structure element. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | Generate ID for structure element. |
| [getActualText()](#getActualText--) | Gets or sets the actual text for structure element. |
| [getAlignment()](#getAlignment--) | Gets or sets the cell alignment. |
| [getAlternativeText()](#getAlternativeText--) | Gets or sets the alternative text for structure element. |
| [getAttributes()](#getAttributes--) | Gets  StructureAttributeCollection  object. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the cell background color. |
| [getBorder()](#getBorder--) | Gets or sets the cell border. |
| [getCell()](#getCell--) |  |
| [getChildElements()](#getChildElements--) | Gets children collection of  Element  objects. |
| [getClass()](#getClass--) |  |
| [getColSpan()](#getColSpan--) | Gets or sets the column span. |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets or sets the default cell text state. |
| [getElementEngine()](#getElementEngine--) | Get parent element. |
| [getExpansionText()](#getExpansionText--) | Gets or sets the expansion text for structure element. |
| [getID()](#getID--) | Gets the ID for structure element. |
| [getLanguage()](#getLanguage--) | Gets or sets the language for structure element. |
| [getMargin()](#getMargin--) | Gets or sets the padding. |
| [getParentElement()](#getParentElement--) | Gets parent collection of  Element  objects. |
| [getRowSpan()](#getRowSpan--) | Gets or sets the row span. |
| [getS()](#getS--) |  |
| [getStructureTextState()](#getStructureTextState--) | Gets  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element. |
| [getStructureType()](#getStructureType--) | Gets type of structure element. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | Gets or sets the title for structure element. |
| [getTrailer()](#getTrailer--) | Internam method |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets or sets the vertical alignment. |
| [hashCode()](#hashCode--) |  |
| [isNoBorder()](#isNoBorder--) | Gets or sets the cell have border. |
| [isWordWrapped()](#isWordWrapped--) | Gets or sets the cell's text word wrapped. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Gets or sets the actual text for structure element. |
| [setAlignment(int value)](#setAlignment-int-) | Gets or sets the cell alignment. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gets or sets the alternative text for structure element. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the cell background color. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the cell border. |
| [setColSpan(int value)](#setColSpan-int-) | Gets or sets the column span. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets the default cell text state. |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Gets or sets the expansion text for structure element. |
| [setId(String id)](#setId-java.lang.String-) | Sets ID for structure element. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Gets or sets the language for structure element. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Gets or sets the padding. |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | Gets or sets the cell have border. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | set Parent Element |
| [setRowSpan(int value)](#setRowSpan-int-) | Gets or sets the row span. |
| [setTag(String newTag)](#setTag-java.lang.String-) | Sets custom tag for structure element. |
| [setText(String text)](#setText-java.lang.String-) | Appends text content to current text element. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets the title for structure element. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Gets or sets the vertical alignment. |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Gets or sets the cell's text word wrapped. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Gets or sets the cell alignment.

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


Gets or sets the cell background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color instance
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets or sets the cell border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### getCell() {#getCell--}
```
public final Cell getCell()
```




**Returns:**
[Cell](../../com.aspose.pdf/cell)
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
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


Gets or sets the column span.

**Returns:**
int - int value
### getDefaultAttributeOwner() {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```


Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object.

Value:  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object.

**Returns:**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - AttributeOwnerStandard instance
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Gets or sets the default cell text state.

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
### getMargin() {#getMargin--}
```
public final MarginInfo getMargin()
```


Gets or sets the padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo instance
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Gets parent collection of  Element  objects.

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Value: Parent collection of  Element  objects.
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```


Gets or sets the row span.

**Returns:**
int - int value
### getS() {#getS--}
```
public final IPdfName getS()
```




**Returns:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
### getStructureTextState() {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```


Gets  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element.

Value:  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element.

**Returns:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - StructureTextState instance
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
### isNoBorder() {#isNoBorder--}
```
public final boolean isNoBorder()
```


Gets or sets the cell have border.

**Returns:**
boolean - boolean value
### isWordWrapped() {#isWordWrapped--}
```
public final boolean isWordWrapped()
```


Gets or sets the cell's text word wrapped.

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


Gets or sets the cell alignment.

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


Gets or sets the cell background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color instance |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Gets or sets the cell border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

### setColSpan(int value) {#setColSpan-int-}
```
public final void setColSpan(int value)
```


Gets or sets the column span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Gets or sets the default cell text state.

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

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


Gets or sets the padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo instance |

### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```


Gets or sets the cell have border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


set Parent Element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | value |

### setRowSpan(int value) {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```


Gets or sets the row span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setTag(String newTag) {#setTag-java.lang.String-}
```
public final void setTag(String newTag)
```


Sets custom tag for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newTag | java.lang.String | Tag name |

### setText(String text) {#setText-java.lang.String-}
```
public final void setText(String text)
```


Appends text content to current text element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content |

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

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```


Gets or sets the cell's text word wrapped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

