---
title: FitRExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and.
type: docs
weight: 1570
url: /java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.

## Constructors

| Constructor | Description |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Creates remote explicit destination. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Creates remote explicit destination. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Creates the instance and initializes it by DOM page object and visible parameters. |

## Methods

| Method | Description |
| --- | --- |
| [getBottom](#getBottom--) | Gets bottom vertical coordinate of visible rectangle. |
| [getLeft](#getLeft--) | Gets left horizontal coordinate of visible rectangle. |
| [getRight](#getRight--) | Gets right horizontal coordinate of visible rectangle. |
| [getTop](#getTop--) | Gets top vertical coordinate of visible rectangle. |
| [toString](#toString--) | Converts the object state into string value. Example: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Creates remote explicit destination.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The destination page number of remote document. |
| left |  | Left horizontal coordinate of visible rectangle. |
| bottom |  | Bottom vertical coordinate of visible rectangle. |
| right |  | Right horizontal coordinate of visible rectangle. |
| top |  | Top vertical coordinate of visible rectangle. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Creates the instance and initializes it by DOM page object and visible parameters.

### getBottom {#getBottom--}
```
public double getBottom()
```

Gets bottom vertical coordinate of visible rectangle.

**Returns:**
double value

### getLeft {#getLeft--}
```
public double getLeft()
```

Gets left horizontal coordinate of visible rectangle.

**Returns:**
double value

### getRight {#getRight--}
```
public double getRight()
```

Gets right horizontal coordinate of visible rectangle.

**Returns:**
double value

### getTop {#getTop--}
```
public double getTop()
```

Gets top vertical coordinate of visible rectangle.

**Returns:**
double value

### toString {#toString--}
```
public String toString()
```

Converts the object state into string value. Example: "1 FitR 100 200 300 400".

**Returns:**
String value representing object state.
