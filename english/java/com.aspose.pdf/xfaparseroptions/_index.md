---
title: XfaParserOptions
linktitle: XfaParserOptions
second_title: Aspose.PDF for Java API Reference
description: class to handle related data encapsulation
type: docs
weight: 5560
url: /java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

class to handle related data encapsulation

## Constructors

| Constructor | Description |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | Initializes a new instance of the {@code XfaParserOptions} class. |

## Methods

| Method | Description |
| --- | --- |
| [getBasePath](#getBasePath--) | Gets or sets the base path. Value: The base path. |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default. |
| [getPageSize](#getPageSize--) | Gets or sets the size of the page. Value: The size of the page. |
| [getSigned](#getSigned--) | If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature. |
| [setBasePath](#setBasePath-java.net.URI-) | Gets or sets the base path. Value: The base path. |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default. |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | Gets or sets the size of the page. Value: The size of the page. |
| [setSigned](#setSigned-boolean-) | If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature. |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
Initializes a new instance of the {@code XfaParserOptions} class.

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

Gets or sets the base path. Value: The base path.

**Returns:**
URI object

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default.

**Returns:**
boolean value

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Gets or sets the size of the page. Value: The size of the page.

**Returns:**
Dimension2D object

### getSigned {#getSigned--}
```
public boolean getSigned()
```

If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature.

**Returns:**
boolean value

### setBasePath {#setBasePath-java.net.URI-}
Gets or sets the base path. Value: The base path.

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogies of excluded groups during conversion Xfa representation of forms to standard. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
Gets or sets the size of the page. Value: The size of the page.

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
