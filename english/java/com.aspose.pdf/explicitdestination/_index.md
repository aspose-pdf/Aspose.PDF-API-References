---
title: ExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents the base class for explicit destinations in PDF document.
type: docs
weight: 102
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
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [toString()](#toString--) | Returns string representation of ExplicitDestination object. |
### getPage() {#getPage--}
```
public Page getPage()
```


Gets the destination page object

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets the destination page number

**Returns:**
int - int value
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
### createDestination(IDocument doc, int pageNumber, int type, double[] values) {#createDestination-com.aspose.pdf.IDocument-int-int-double...-}
```
public static ExplicitDestination createDestination(IDocument doc, int pageNumber, int type, double[] values)
```


Creates instances of ExplicitDestination descendant classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Document where destination will be created. |
| pageNumber | int | Number of the page. |
| type | int | Destionatyion type. |
| values | double[] | Array of destination specific values. |

**Returns:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - The explicit destination object.
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
### toString() {#toString--}
```
public abstract String toString()
```


Returns string representation of ExplicitDestination object.

**Returns:**
java.lang.String - String representation
