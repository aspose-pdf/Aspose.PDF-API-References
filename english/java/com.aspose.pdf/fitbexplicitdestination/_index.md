---
title: FitBExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and.
type: docs
weight: 1520
url: /java/com.aspose.pdf/fitbexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension.

## Constructors

| Constructor | Description |
| --- | --- |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | Creates remote explicit destination. |
| [FitBExplicitDestination](#FitBExplicitDestination-int-) | Creates remote explicit destination. |
| [FitBExplicitDestination](#FitBExplicitDestination-com.aspose.pdf.Page-) | Creates the instance and initializes it by DOM page object. |

## Methods

| Method | Description |
| --- | --- |
| [toString](#toString--) | Converts the object state into string value. Example: "1 FitB". |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
Creates remote explicit destination.

### FitBExplicitDestination {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```

Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The destination page number of remote document. |

### FitBExplicitDestination {#FitBExplicitDestination-com.aspose.pdf.Page-}
Creates the instance and initializes it by DOM page object.

### toString {#toString--}
```
public String toString()
```

Converts the object state into string value. Example: "1 FitB".

**Returns:**
String value representing object state.
