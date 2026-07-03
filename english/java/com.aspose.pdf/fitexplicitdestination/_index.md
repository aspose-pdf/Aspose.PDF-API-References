---
title: FitExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the.
type: docs
weight: 1550
url: /java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the page within the window in the other dimension.

## Constructors

| Constructor | Description |
| --- | --- |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Document-int-) | Creates remote explicit destination. |
| [FitExplicitDestination](#FitExplicitDestination-int-) | Creates remote explicit destination. |
| [FitExplicitDestination](#FitExplicitDestination-com.aspose.pdf.Page-) | Creates local explicit destination. |

## Methods

| Method | Description |
| --- | --- |
| [toString](#toString--) | Converts the object state into string value. Example: "1 Fit". |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Document-int-}
Creates remote explicit destination.

### FitExplicitDestination {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
```

Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The destination page number of remote document. |

### FitExplicitDestination {#FitExplicitDestination-com.aspose.pdf.Page-}
Creates local explicit destination.

### toString {#toString--}
```
public String toString()
```

Converts the object state into string value. Example: "1 Fit".

**Returns:**
String value representing object state.
