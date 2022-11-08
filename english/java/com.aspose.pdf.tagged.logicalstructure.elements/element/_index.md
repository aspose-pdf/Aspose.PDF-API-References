---
title: Element
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for element in logical structure.
type: docs
weight: 10
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object
```
public abstract class Element
```

Represents a base class for element in logical structure.
## Methods

| Method | Description |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Find Elements of a given type |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Find Elements of a given type |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Append  /Aspose.Pdf.LogicalStructure.Element  to collection of children. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildElements()](#getChildElements--) | Gets children collection of  Element  objects. |
| [getClass()](#getClass--) |  |
| [getElementEngine()](#getElementEngine--) | Get parent element. |
| [getParentElement()](#getParentElement--) | Gets parent collection of  Element  objects. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTrailer()](#getTrailer--) | Internam method |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
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
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Gets parent collection of  Element  objects.

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Value: Parent collection of  Element  objects.
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

