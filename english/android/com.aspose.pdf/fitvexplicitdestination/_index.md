---
title: FitVExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window.
type: docs
weight: 108
url: /java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitVExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.
## Constructors

| Constructor | Description |
| --- | --- |
| [FitVExplicitDestination(Page page, double left)](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Creates the instance and initializes it by DOM page object and left parameter. |
## Methods

| Method | Description |
| --- | --- |
| [getLeft()](#getLeft--) | Gets the horizontal coordinate left positioned at the left edge of the window. |
| [toString()](#toString--) | Converts the object state into string value. |
### FitVExplicitDestination(Page page, double left) {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
```
public FitVExplicitDestination(Page page, double left)
```


Creates the instance and initializes it by DOM page object and left parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM page object. |
| left | double | The horizontal coordinate left positioned at the left edge of the window. |

### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets the horizontal coordinate left positioned at the left edge of the window.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Converts the object state into string value. Example: "1 FitV 100".

**Returns:**
java.lang.String - String value representing object state.
