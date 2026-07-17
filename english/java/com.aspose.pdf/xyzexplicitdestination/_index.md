---
title: XYZExplicitDestination
linktitle: XYZExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: <p> Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page.
type: docs
weight: 5800
url: /java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Creates remote explicit destination. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Creates remote explicit destination. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Creates the instance and initializes it by DOM page object and visible parameters. |

## Methods

| Method | Description |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Create destination to specified location of the page considering page rotation if required. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Create destination to specified page. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Create destination to upper left corner of the specified page. |
| [getLeft](#getLeft--) | Gets left horizontal coordinate of the upper-left corner of the window. |
| [getTop](#getTop--) | Gets top vertical coordinate of the upper-left corner of the window. |
| [getZoom](#getZoom--) | Gets zoom factor. |
| [toString](#toString--) | Converts the object state into string value. Example: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Creates remote explicit destination.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The destination page number of remote document. |
| left |  | Left horizontal coordinate of the upper-left corner of the window. |
| top |  | Top vertical coordinate of the upper-left corner of the window. |
| zoom |  | Zoom factor. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Creates the instance and initializes it by DOM page object and visible parameters.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Create destination to specified location of the page considering page rotation if required.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Create destination to specified page.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Create destination to upper left corner of the specified page.

### getLeft {#getLeft--}
```
public double getLeft()
```

Gets left horizontal coordinate of the upper-left corner of the window.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Gets top vertical coordinate of the upper-left corner of the window.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Gets zoom factor.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Converts the object state into string value. Example: "1 XYZ 100 200 3".

**Returns:**
String value representing object state.
