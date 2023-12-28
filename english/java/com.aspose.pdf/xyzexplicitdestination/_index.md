---
title: XYZExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with the coordinates left top positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom.
type: docs
weight: 412
url: /java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class XYZExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.

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
| [getLeft()](#getLeft--) | Gets left horizontal coordinate of the upper-left corner of the window. |
| [getTop()](#getTop--) | Gets top vertical coordinate of the upper-left corner of the window. |
| [getZoom()](#getZoom--) | Gets zoom factor. |
| [createDestination(Page page, double left, double top, double zoom, boolean considerRotation)](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Create destination to specified location of the page considering page rotation if required. |
| [createDestinationToUpperLeftCorner(Page page, double zoom)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Create destination to upper left corner of the specified page. |
| [createDestinationToUpperLeftCorner(Page page)](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Create destination to specified page. |
| [toString()](#toString--) | Converts the object state into string value. |
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

### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets left horizontal coordinate of the upper-left corner of the window.

**Returns:**
double - double
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
### toString() {#toString--}
```
public String toString()
```


Converts the object state into string value. Example: "1 XYZ 100 200 3".

**Returns:**
java.lang.String - String value representing object state.
