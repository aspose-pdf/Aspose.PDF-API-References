---
title: IllustrationElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for illustration structure elements in logical structure.
type: docs
weight: 14
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement)
```
public abstract class IllustrationElement extends StructureElement
```

Represents a base class for illustration structure elements in logical structure.
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
| [getAlternativeText()](#getAlternativeText--) | Gets or sets the alternative text for structure element. |
| [getAttributes()](#getAttributes--) | Gets  StructureAttributeCollection  object. |
| [getChildElements()](#getChildElements--) | Gets children collection of  Element  objects. |
| [getClass()](#getClass--) |  |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Gets  /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard  object. |
| [getElementEngine()](#getElementEngine--) | Get parent element. |
| [getExpansionText()](#getExpansionText--) | Gets or sets the expansion text for structure element. |
| [getID()](#getID--) | Gets the ID for structure element. |
| [getLanguage()](#getLanguage--) | Gets or sets the language for structure element. |
| [getParentElement()](#getParentElement--) | Gets parent collection of  Element  objects. |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | Gets type of structure element. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | Gets or sets the title for structure element. |
| [getTrailer()](#getTrailer--) | Internam method |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Gets or sets the actual text for structure element. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gets or sets the alternative text for structure element. |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Gets or sets the expansion text for structure element. |
| [setId(String id)](#setId-java.lang.String-) | Sets ID for structure element. |
| [setImage(String imageSrc)](#setImage-java.lang.String-) | Appends image to current illustration element. |
| [setImage(String imageSrc, double imageResolution)](#setImage-java.lang.String-double-) | Appends image to current illustration element. |
| [setImage(String imageSrc, double imageWidth, double imageHeight)](#setImage-java.lang.String-double-double-) | Appends image to current illustration element. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Gets or sets the language for structure element. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | set Parent Element |
| [setTag(String newTag)](#setTag-java.lang.String-) | Sets custom tag for structure element. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets the title for structure element. |
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setImage(String imageSrc) {#setImage-java.lang.String-}
```
public void setImage(String imageSrc)
```


Appends image to current illustration element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSrc | java.lang.String | Image source. |

### setImage(String imageSrc, double imageResolution) {#setImage-java.lang.String-double-}
```
public void setImage(String imageSrc, double imageResolution)
```


Appends image to current illustration element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSrc | java.lang.String | Image source. |
| imageResolution | double | (Optional) Image Resolution. Default: 300 DPI. |

### setImage(String imageSrc, double imageWidth, double imageHeight) {#setImage-java.lang.String-double-double-}
```
public void setImage(String imageSrc, double imageWidth, double imageHeight)
```


Appends image to current illustration element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSrc | java.lang.String | Image source. |
| imageWidth | double | Image width. |
| imageHeight | double | Image height. |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Gets or sets the language for structure element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value: Language of the structure element. |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


set Parent Element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | value |

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

