---
title: FitHExplicitDestination
linktitle: FitHExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just.
type: docs
weight: 1560
url: /java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.

## Constructors

| Constructor | Description |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | Creates remote explicit destination. |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | Creates remote explicit destination. |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | Creates the instance and initializes it by DOM page object and top parameter. |

## Methods

| Method | Description |
| --- | --- |
| [getTop](#getTop--) | Gets the vertical coordinate top positioned at the top edge of the window. |
| [toString](#toString--) | Converts the object state into string value. Example: "1 FitH 100". |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
Creates remote explicit destination.

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The destination page number of remote document. |
| top |  | The vertical coordinate top positioned at the top edge of the window. |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
Creates the instance and initializes it by DOM page object and top parameter.

### getTop {#getTop--}
```
public double getTop()
```

Gets the vertical coordinate top positioned at the top edge of the window.

**Returns:**
double value

### toString {#toString--}
```
public String toString()
```

Converts the object state into string value. Example: "1 FitH 100".

**Returns:**
String value representing object state.
