---
title: FitRExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left bottom right and topentirely within the window both horizontally and vertically.
type: docs
weight: 124
url: /java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitRExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.
## Constructors

| Constructor | Description |
| --- | --- |
| [FitRExplicitDestination(Page page, double left, double bottom, double right, double top)](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Creates the instance and initializes it by DOM page object and visible parameters. |
| [FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top)](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Creates remote explicit destination. |
| [FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)](#FitRExplicitDestination-int-double-double-double-double-) | Creates remote explicit destination. |
## Methods

| Method | Description |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | Creates instance of ExplicitDestination descendant classes. |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Gets bottom vertical coordinate of visible rectangle. |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | Gets left horizontal coordinate of visible rectangle. |
| [getPage()](#getPage--) | Gets the destination page object |
| [getPageNumber()](#getPageNumber--) | Gets the destination page number |
| [getRight()](#getRight--) | Gets right horizontal coordinate of visible rectangle. |
| [getTop()](#getTop--) | Gets top vertical coordinate of visible rectangle. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Converts the object state into string value. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FitRExplicitDestination(Page page, double left, double bottom, double right, double top) {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
```
public FitRExplicitDestination(Page page, double left, double bottom, double right, double top)
```


Creates the instance and initializes it by DOM page object and visible parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM page object. |
| left | double | Left horizontal coordinate of visible rectangle. |
| bottom | double | Bottom vertical coordinate of visible rectangle. |
| right | double | Right horizontal coordinate of visible rectangle. |
| top | double | Top vertical coordinate of visible rectangle. |

### FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top) {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
```
public FitRExplicitDestination(Document document, int pageNumber, double left, double bottom, double right, double top)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | The parent document that contains this object. |
| pageNumber | int | The destination page number of remote document. |
| left | double | Left horizontal coordinate of visible rectangle. |
| bottom | double | Bottom vertical coordinate of visible rectangle. |
| right | double | Right horizontal coordinate of visible rectangle. |
| top | double | Top vertical coordinate of visible rectangle. |

### FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top) {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The destination page number of remote document. |
| left | double | Left horizontal coordinate of visible rectangle. |
| bottom | double | Bottom vertical coordinate of visible rectangle. |
| right | double | Right horizontal coordinate of visible rectangle. |
| top | double | Top vertical coordinate of visible rectangle. |

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
### createDestination(IPdfArray engineDest) {#createDestination-com.aspose.pdf.engine.data.IPdfArray-}
```
public static ExplicitDestination createDestination(IPdfArray engineDest)
```


Creates instance of ExplicitDestination descendant classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| engineDest | [IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray) | Engine destination object. |

**Returns:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) - DOM explicit destination object.
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
### getBottom() {#getBottom--}
```
public double getBottom()
```


Gets bottom vertical coordinate of visible rectangle.

**Returns:**
double - double value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets left horizontal coordinate of visible rectangle.

**Returns:**
double - double value
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
### getRight() {#getRight--}
```
public double getRight()
```


Gets right horizontal coordinate of visible rectangle.

**Returns:**
double - double value
### getTop() {#getTop--}
```
public double getTop()
```


Gets top vertical coordinate of visible rectangle.

**Returns:**
double - double value
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




### toString() {#toString--}
```
public String toString()
```


Converts the object state into string value. Example: "1 FitR 100 200 300 400".

**Returns:**
java.lang.String - String value representing object state.
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

