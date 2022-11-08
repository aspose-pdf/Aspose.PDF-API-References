---
title: StructTreeRootElement
second_title: Aspose.PDF for Java API Reference
description: Represents StructTreeRoot object in logical structure.
type: docs
weight: 14
url: /java/com.aspose.pdf.tagged.logicalstructure/structtreerootelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public final class StructTreeRootElement extends Element
```

Represents StructTreeRoot object in logical structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#StructTreeRootElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
## Methods

| Method | Description |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Find Elements of a given type |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Find Elements of a given type |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Append  /Aspose.Pdf.LogicalStructure.Element  to collection of children. |
| [createStructParents()](#createStructParents--) |  |
| [doPreSave()](#doPreSave--) |  |
| [doSave()](#doSave--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllElements()](#getAllElements--) |  |
| [getChildElements()](#getChildElements--) | Gets children collection of  Element  objects. |
| [getClass()](#getClass--) |  |
| [getElementEngine()](#getElementEngine--) | Get parent element. |
| [getIDTree()](#getIDTree--) |  |
| [getParentElement()](#getParentElement--) | Gets parent collection of  Element  objects. |
| [getRoleMap()](#getRoleMap--) |  |
| [getStructParentsArray(IPdfNumber structParents)](#getStructParentsArray-com.aspose.pdf.engine.data.IPdfNumber-) |  |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTrailer()](#getTrailer--) | Internam method |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registrationObjectInParentTree(IPdfObject pdfObject)](#registrationObjectInParentTree-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#StructTreeRootElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) |  |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

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
### createStructParents() {#createStructParents--}
```
public final IPdfNumber createStructParents()
```




**Returns:**
[IPdfNumber](../../com.aspose.pdf.engine.data/ipdfnumber)
### doPreSave() {#doPreSave--}
```
public final void doPreSave()
```




### doSave() {#doSave--}
```
public final void doSave()
```




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
### getAllElements() {#getAllElements--}
```
public final System.Collections.Generic.List<Element> getAllElements()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.tagged.logicalstructure.elements.Element>
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
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


Get parent element.

**Returns:**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - Value: Parent element.
### getIDTree() {#getIDTree--}
```
public final NamesTreeNode getIDTree()
```




**Returns:**
[NamesTreeNode](../../com.aspose.pdf.engine.commondata/namestreenode)
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Gets parent collection of  Element  objects.

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Value: Parent collection of  Element  objects.
### getRoleMap() {#getRoleMap--}
```
public final IPdfDictionary getRoleMap()
```




**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getStructParentsArray(IPdfNumber structParents) {#getStructParentsArray-com.aspose.pdf.engine.data.IPdfNumber-}
```
public final IPdfArray getStructParentsArray(IPdfNumber structParents)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structParents | [IPdfNumber](../../com.aspose.pdf.engine.data/ipdfnumber) |  |

**Returns:**
[IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray)
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```




**Returns:**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent)
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




### registrationObjectInParentTree(IPdfObject pdfObject) {#registrationObjectInParentTree-com.aspose.pdf.engine.data.IPdfObject-}
```
public final int registrationObjectInParentTree(IPdfObject pdfObject)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfObject | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

**Returns:**
int
### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

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

