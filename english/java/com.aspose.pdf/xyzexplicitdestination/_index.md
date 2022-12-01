---
title: XYZExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with the coordinates left top positioned at the upper left corner of the window and the contents of the page magnified by the factor zoom.
type: docs
weight: 411
url: /java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class XYZExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.

--------------------

Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get\_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom();
## Constructors

| Constructor | Description |
| --- | --- |
| [XYZExplicitDestination(Page page, double left, double top, double zoom)](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Creates the instance and initializes it by DOM page object and visible parameters. |
| [XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom)](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Creates remote explicit destination. |
| [XYZExplicitDestination(int pageNumber, double left, double top, double zoom)](#XYZExplicitDestination-int-double-double-double-) | Creates remote explicit destination. |
## Methods

| Method | Description |
| --- | --- |
| [createDestination(IDocument doc, int pageNumber, int type, double[] values)](#createDestination-com.aspose.pdf.IDocument-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(Page page, double left, double top, double zoom, boolean considerRotation)](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Create destination to specified location of the page considering page rotation if required. |
| [createDestination(Page page, int type, double[] values)](#createDestination-com.aspose.pdf.Page-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestination(IPdfArray engineDest)](#createDestination-com.aspose.pdf.engine.data.IPdfArray-) | Creates instance of ExplicitDestination descendant classes. |
| [createDestination(int pageNumber, int type, double[] values)](#createDestination-int-int-double...-) | Creates instances of ExplicitDestination descendant classes. |
| [createDestinationToUpperLeftCorner(Page page)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Create destination to specified page. |
| [createDestinationToUpperLeftCorner(Page page, double zoom)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Create destination to upper left corner of the specified page. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeft()](#getLeft--) | Gets left horizontal coordinate of the upper-left corner of the window. |
| [getPage()](#getPage--) | Gets the destination page object |
| [getPageNumber()](#getPageNumber--) | Gets the destination page number |
| [getTop()](#getTop--) | Gets top vertical coordinate of the upper-left corner of the window. |
| [getZoom()](#getZoom--) | Gets zoom factor. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Converts the object state into string value. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XYZExplicitDestination(Page page, double left, double top, double zoom) {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
```
public XYZExplicitDestination(Page page, double left, double top, double zoom)
```


Creates the instance and initializes it by DOM page object and visible parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM page object. |
| left | double | Left horizontal coordinate of the upper-left corner of the window. |
| top | double | Top vertical coordinate of the upper-left corner of the window. |
| zoom | double | Zoom factor. |

### XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom) {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
```
public XYZExplicitDestination(IDocument document, int pageNumber, double left, double top, double zoom)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The parent document that contains this object. |
| pageNumber | int | The destination page number of remote document. |
| left | double | Left horizontal coordinate of the upper-left corner of the window. |
| top | double | Top vertical coordinate of the upper-left corner of the window. |
| zoom | double | Zoom factor. |

### XYZExplicitDestination(int pageNumber, double left, double top, double zoom) {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The destination page number of remote document. |
| left | double | Left horizontal coordinate of the upper-left corner of the window. |
| top | double | Top vertical coordinate of the upper-left corner of the window. |
| zoom | double | Zoom factor. |

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
### createDestination(Page page, double left, double top, double zoom, boolean considerRotation) {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
```
public static XYZExplicitDestination createDestination(Page page, double left, double top, double zoom, boolean considerRotation)
```


Create destination to specified location of the page considering page rotation if required.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Destination page. |
| left | double | Left position on the page. |
| top | double | Top position on the page. |
| zoom | double | Zoom factor (0 for default). |
| considerRotation | boolean | If true position will be recalculated according to page rotation. |

**Returns:**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - Destination object.
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
### createDestinationToUpperLeftCorner(Page page) {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
```
public static XYZExplicitDestination createDestinationToUpperLeftCorner(Page page)
```


Create destination to specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Destination page. |

**Returns:**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - Destination object.
### createDestinationToUpperLeftCorner(Page page, double zoom) {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
```
public static XYZExplicitDestination createDestinationToUpperLeftCorner(Page page, double zoom)
```


Create destination to upper left corner of the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Destination page. |
| zoom | double | Zoom factor. |

**Returns:**
[XYZExplicitDestination](../../com.aspose.pdf/xyzexplicitdestination) - Destination object.
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
### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets left horizontal coordinate of the upper-left corner of the window.

**Returns:**
double - double
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


Gets top vertical coordinate of the upper-left corner of the window.

**Returns:**
double - double
### getZoom() {#getZoom--}
```
public double getZoom()
```


Gets zoom factor.

**Returns:**
double - double
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


Converts the object state into string value. Example: "1 XYZ 100 200 3".

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

