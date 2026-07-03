---
title: FitBVExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just.
type: docs
weight: 1540
url: /java/com.aspose.pdf/fitbvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBVExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.

## Constructors

| Constructor | Description |
| --- | --- |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-) | Creates remote explicit destination. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-int-double-) | Creates remote explicit destination. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Page-double-) | Creates the instance and initializes it by DOM page object and left parameter. |

## Methods

| Method | Description |
| --- | --- |
| [getLeft](#getLeft--) | Gets the horizontal coordinate left positioned at the left edge of the window. |
| [toString](#toString--) | Converts the object state into string value. Example: "1 FitBV 100". |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-}
Creates remote explicit destination.

### FitBVExplicitDestination {#FitBVExplicitDestination-int-double-}
```
public FitBVExplicitDestination(int pageNumber, double left)
```

Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The destination page number of remote document. |
| left |  | The horizontal coordinate left positioned at the left edge of the window. |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Page-double-}
Creates the instance and initializes it by DOM page object and left parameter.

### getLeft {#getLeft--}
```
public double getLeft()
```

Gets the horizontal coordinate left positioned at the left edge of the window.

**Returns:**
double value

### toString {#toString--}
```
public String toString()
```

Converts the object state into string value. Example: "1 FitBV 100".

**Returns:**
String value representing object state.
