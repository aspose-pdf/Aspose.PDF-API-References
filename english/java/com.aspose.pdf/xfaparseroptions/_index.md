---
title: XfaParserOptions
second_title: Aspose.PDF for Java API Reference
description: class to handle related data encapsulation
type: docs
weight: 412
url: /java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object
```
public class XfaParserOptions
```

class to handle related data encapsulation
## Constructors

| Constructor | Description |
| --- | --- |
| [XfaParserOptions(Dimension2D pageSize)](#XfaParserOptions-java.awt.geom.Dimension2D-) | Initializes a new instance of the  XfaParserOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | Gets or sets the base path. |
| [getClass()](#getClass--) |  |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. |
| [getPageSize()](#getPageSize--) | Gets or sets the size of the page. |
| [getSigned()](#getSigned--) | If this property is true then document will be converted with using of xfa form stream (if it exists). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasePath(URI value)](#setBasePath-java.net.URI-) | Gets or sets the base path. |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. |
| [setPageSize(Dimension2D value)](#setPageSize-java.awt.geom.Dimension2D-) | Gets or sets the size of the page. |
| [setSigned(boolean value)](#setSigned-boolean-) | If this property is true then document will be converted with using of xfa form stream (if it exists). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XfaParserOptions(Dimension2D pageSize) {#XfaParserOptions-java.awt.geom.Dimension2D-}
```
public XfaParserOptions(Dimension2D pageSize)
```


Initializes a new instance of the  XfaParserOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | Size of the page. |

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
### getBasePath() {#getBasePath--}
```
public URI getBasePath()
```


Gets or sets the base path.

Value: The base path.

**Returns:**
java.net.URI - URI object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default.

**Returns:**
boolean - boolean value
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Gets or sets the size of the page.

Value: The size of the page.

**Returns:**
java.awt.geom.Dimension2D - Dimension2D object
### getSigned() {#getSigned--}
```
public boolean getSigned()
```


If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature.

**Returns:**
boolean - boolean value
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




### setBasePath(URI value) {#setBasePath-java.net.URI-}
```
public void setBasePath(URI value)
```


Gets or sets the base path.

Value: The base path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI | URI object |

### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setPageSize(Dimension2D value) {#setPageSize-java.awt.geom.Dimension2D-}
```
public void setPageSize(Dimension2D value)
```


Gets or sets the size of the page.

Value: The size of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D | Dimension2D object |

### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

