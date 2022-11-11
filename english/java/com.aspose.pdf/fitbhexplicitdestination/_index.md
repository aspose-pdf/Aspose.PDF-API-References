---
title: FitBHExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with the vertical coordinate to positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window.
type: docs
weight: 120
url: /java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.
## Constructors

| Constructor | Description |
| --- | --- |
| [FitBHExplicitDestination(Page page, double top)](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Creates the instance and initializes it by DOM page object and top parameter. |
| [FitBHExplicitDestination(Document document, int pageNumber, double top)](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Creates remote explicit destination. |
| [FitBHExplicitDestination(int pageNumber, double top)](#FitBHExplicitDestination-int-double-) | Creates remote explicit destination. |
## Methods

| Method | Description |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | Creates instance of ExplicitDestination descendant classes. |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPage()](#getPage--) | Gets the destination page object |
| [getPageNumber()](#getPageNumber--) | Gets the destination page number |
| [getTop()](#getTop--) | Gets the vertical coordinate top positioned at the top edge of the window. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Converts the object state into string value. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FitBHExplicitDestination(Page page, double top) {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
```
public FitBHExplicitDestination(Page page, double top)
```


Creates the instance and initializes it by DOM page object and top parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM page object. |
| top | double | The vertical coordinate top positioned at the top edge of the window. |

### FitBHExplicitDestination(Document document, int pageNumber, double top) {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
```
public FitBHExplicitDestination(Document document, int pageNumber, double top)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | The parent document that contains this object. |
| pageNumber | int | The destination page number of remote document. |
| top | double | The vertical coordinate top positioned at the top edge of the window. |

### FitBHExplicitDestination(int pageNumber, double top) {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The destination page number of remote document. |
| top | double | The vertical coordinate top positioned at the top edge of the window. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTop() {#getTop--}
```
public double getTop()
```


Gets the vertical coordinate top positioned at the top edge of the window.

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


Converts the object state into string value. Example: "1 FitBH 100".

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

