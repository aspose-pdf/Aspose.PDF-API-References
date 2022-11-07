---
title: ExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents the base class for explicit destinations in PDF document.
type: docs
weight: 87
url: /java/com.aspose.pdf/explicitdestination/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.IAppointment](../../com.aspose.pdf/iappointment)
```
public abstract class ExplicitDestination implements IAppointment
```

Represents the base class for explicit destinations in PDF document.
## Methods

| Method | Description |
| --- | --- |
| [getPage()](#getPage--) | Gets the destination page object |
| [getPageNumber()](#getPageNumber--) | Gets the destination page number |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(Document doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.Document-int-int-double...-) |  |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
### getPage() {#getPage--}
```
public Page getPage()
```


Gets the destination page object

**Returns:**
[Page](../../com.aspose.pdf/page)
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets the destination page number

**Returns:**
int
### createDestination(IPdfArray engineDest) {#createDestination-com.aspose.pdf.engine.data.IPdfArray-}
```
public static ExplicitDestination createDestination(IPdfArray engineDest)
```


Creates instances of ExplicitDestination descendant classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| engineDest | [IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray) | Engine destination object. |

**Returns:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - DOM explicit destination object.
### createDestination(Page page, int type, double[] values) {#createDestination-com.aspose.pdf.Page-int-double...-}
```
public static ExplicitDestination createDestination(Page page, int type, double[] values)
```


Creates instances of ExplicitDestination descendant classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The object of destination page. |
| type | int | The type of explicit destination. |
| values | double[] | Array of double values. |

**Returns:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - The explicit destination object.
### createDestination(Document doc, int pageNumber, int type, double[] values) {#createDestination-com.aspose.pdf.Document-int-int-double...-}
```
public static ExplicitDestination createDestination(Document doc, int pageNumber, int type, double[] values)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) |  |
| pageNumber | int |  |
| type | int |  |
| values | double[] |  |

**Returns:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - 
### createDestination(int pageNumber, int type, double[] values) {#createDestination-int-int-double...-}
```
public static ExplicitDestination createDestination(int pageNumber, int type, double[] values)
```


Creates instances of ExplicitDestination descendant classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The destination page number. |
| type | int | The type of explicit destination. |
| values | double[] | Array of double values. |

**Returns:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - The explicit destination object.
