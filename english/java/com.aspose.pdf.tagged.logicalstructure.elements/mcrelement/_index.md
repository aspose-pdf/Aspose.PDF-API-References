---
title: MCRElement
second_title: Aspose.PDF for Java API Reference
description: Represents marked-content reference object in logical structure.
type: docs
weight: 15
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public final class MCRElement extends Element
```

Represents marked-content reference object in logical structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Find Elements of a given type |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Find Elements of a given type |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Append  /Aspose.Pdf.LogicalStructure.Element  to collection of children. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildElements()](#getChildElements--) | Gets children collection of  Element  objects. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Gets text content for marked-content reference element. |
| [getElementEngine()](#getElementEngine--) | Get parent element. |
| [getImageHeight()](#getImageHeight--) | For internal usage only |
| [getImageResolution()](#getImageResolution--) | For internal usage only |
| [getImageSrc()](#getImageSrc--) | Gets image source for marked-content reference element. |
| [getImageWidth()](#getImageWidth--) | For internal usage only |
| [getMCID()](#getMCID--) | Gets MCID of marked-content reference object. |
| [getPage()](#getPage--) | Get Page instance |
| [getParentElement()](#getParentElement--) | Gets parent collection of  Element  objects. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTrailer()](#getTrailer--) | Internam method |
| [hashCode()](#hashCode--) |  |
| [isCreatedElement()](#isCreatedElement--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBdcOperator(BDC value)](#setBdcOperator-com.aspose.pdf.operators.BDC-) | Set BDC Operator |
| [setContent(String value)](#setContent-java.lang.String-) | Gets text content for marked-content reference element. |
| [setHyperlink(Hyperlink hyperlink)](#setHyperlink-com.aspose.pdf.Hyperlink-) |  |
| [setImageHeight(Double[] value)](#setImageHeight-java.lang.Double---) | For internal usage only |
| [setImageResolution(Double[] value)](#setImageResolution-java.lang.Double---) | For internal usage only |
| [setImageSrc(String value)](#setImageSrc-java.lang.String-) | Gets image source for marked-content reference element. |
| [setImageWidth(Double[] value)](#setImageWidth-java.lang.Double---) | For internal usage only |
| [setNewMCID(int value)](#setNewMCID-int-) | Get MCID value |
| [setPage(Page value)](#setPage-com.aspose.pdf.Page-) | Set Page instance |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) | TaggedContext instance |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Internal instance |

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
### getContent() {#getContent--}
```
public final String getContent()
```


Gets text content for marked-content reference element.

For just created object wich implement [ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement). Is null in other cases.

**Returns:**
java.lang.String - Text content for marked-content reference element.
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


Get parent element.

**Returns:**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - Value: Parent element.
### getImageHeight() {#getImageHeight--}
```
public final Double[] getImageHeight()
```


For internal usage only

**Returns:**
java.lang.Double[] - For internal usage only
### getImageResolution() {#getImageResolution--}
```
public final Double[] getImageResolution()
```


For internal usage only

**Returns:**
java.lang.Double[] - For internal usage only
### getImageSrc() {#getImageSrc--}
```
public final String getImageSrc()
```


Gets image source for marked-content reference element.

For just created [IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement). Is null in other cases.

**Returns:**
java.lang.String - Image source for marked-content reference element.
### getImageWidth() {#getImageWidth--}
```
public final Double[] getImageWidth()
```


For internal usage only

**Returns:**
java.lang.Double[] - For internal usage only
### getMCID() {#getMCID--}
```
public final int getMCID()
```


Gets MCID of marked-content reference object.

**Returns:**
int - MCID of marked-content reference object.
### getPage() {#getPage--}
```
public final Page getPage()
```


Get Page instance

**Returns:**
[Page](../../com.aspose.pdf/page) - Page instance
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
### isCreatedElement() {#isCreatedElement--}
```
public final boolean isCreatedElement()
```




**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBdcOperator(BDC value) {#setBdcOperator-com.aspose.pdf.operators.BDC-}
```
public final void setBdcOperator(BDC value)
```


Set BDC Operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BDC](../../com.aspose.pdf.operators/bdc) | BDC Operator |

### setContent(String value) {#setContent-java.lang.String-}
```
public final void setContent(String value)
```


Gets text content for marked-content reference element.

For just created object wich implement [ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement). Is null in other cases.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Text content for marked-content reference element. |

### setHyperlink(Hyperlink hyperlink) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public final void setHyperlink(Hyperlink hyperlink)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hyperlink | [Hyperlink](../../com.aspose.pdf/hyperlink) |  |

### setImageHeight(Double[] value) {#setImageHeight-java.lang.Double---}
```
public final void setImageHeight(Double[] value)
```


For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double[] | For internal usage only |

### setImageResolution(Double[] value) {#setImageResolution-java.lang.Double---}
```
public final void setImageResolution(Double[] value)
```


For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double[] | For internal usage only |

### setImageSrc(String value) {#setImageSrc-java.lang.String-}
```
public final void setImageSrc(String value)
```


Gets image source for marked-content reference element.

For just created [IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement). Is null in other cases.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Image source for marked-content reference element. |

### setImageWidth(Double[] value) {#setImageWidth-java.lang.Double---}
```
public final void setImageWidth(Double[] value)
```


For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double[] | For internal usage only |

### setNewMCID(int value) {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```


Get MCID value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | MCID value |

### setPage(Page value) {#setPage-com.aspose.pdf.Page-}
```
public final void setPage(Page value)
```


Set Page instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | Page instance |

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

