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
| [getPageSize()](#getPageSize--) | Gets or sets the size of the page. |
| [setPageSize(Dimension2D value)](#setPageSize-java.awt.geom.Dimension2D-) | Gets or sets the size of the page. |
| [getSigned()](#getSigned--) | If this property is true then document will be converted with using of xfa form stream (if it exists). |
| [setSigned(boolean value)](#setSigned-boolean-) | If this property is true then document will be converted with using of xfa form stream (if it exists). |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. |
| [getBasePath()](#getBasePath--) | Gets or sets the base path. |
| [setBasePath(URI value)](#setBasePath-java.net.URI-) | Gets or sets the base path. |
### XfaParserOptions(Dimension2D pageSize) {#XfaParserOptions-java.awt.geom.Dimension2D-}
```
public XfaParserOptions(Dimension2D pageSize)
```


Initializes a new instance of the  XfaParserOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | Size of the page. |

### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Gets or sets the size of the page.

Value: The size of the page.

**Returns:**
java.awt.geom.Dimension2D - Dimension2D object
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

### getSigned() {#getSigned--}
```
public boolean getSigned()
```


If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature.

**Returns:**
boolean - boolean value
### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default.

**Returns:**
boolean - boolean value
### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getBasePath() {#getBasePath--}
```
public URI getBasePath()
```


Gets or sets the base path.

Value: The base path.

**Returns:**
java.net.URI - URI object
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

