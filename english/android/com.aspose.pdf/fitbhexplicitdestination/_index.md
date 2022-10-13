---
title: FitBHExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window.
type: docs
weight: 103
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
## Methods

| Method | Description |
| --- | --- |
| [getTop()](#getTop--) | Gets the vertical coordinate top positioned at the top edge of the window. |
| [toString()](#toString--) | Converts the object state into string value. |
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

### getTop() {#getTop--}
```
public double getTop()
```


Gets the vertical coordinate top positioned at the top edge of the window.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Converts the object state into string value. Example: "1 FitBH 100".

**Returns:**
java.lang.String - String value representing object state.
