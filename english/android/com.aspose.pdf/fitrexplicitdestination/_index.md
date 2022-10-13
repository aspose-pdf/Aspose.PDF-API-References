---
title: FitRExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left bottom right and topentirely within the window both horizontally and vertically.
type: docs
weight: 107
url: /java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitRExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.
## Constructors

| Constructor | Description |
| --- | --- |
| [FitRExplicitDestination(Page page, double left, double bottom, double right, double top)](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Creates the instance and initializes it by DOM page object and visible parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getLeft()](#getLeft--) | Gets left horizontal coordinate of visible rectangle. |
| [getBottom()](#getBottom--) | Gets bottom vertical coordinate of visible rectangle. |
| [getRight()](#getRight--) | Gets right horizontal coordinate of visible rectangle. |
| [getTop()](#getTop--) | Gets top vertical coordinate of visible rectangle. |
| [toString()](#toString--) | Converts the object state into string value. |
### FitRExplicitDestination(Page page, double left, double bottom, double right, double top) {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
```
public FitRExplicitDestination(Page page, double left, double bottom, double right, double top)
```


Creates the instance and initializes it by DOM page object and visible parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM page object. |
| left | double | Left horizontal coordinate of visible rectangle. |
| bottom | double | Bottom vertical coordinate of visible rectangle. |
| right | double | Right horizontal coordinate of visible rectangle. |
| top | double | Top vertical coordinate of visible rectangle. |

### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets left horizontal coordinate of visible rectangle.

**Returns:**
double
### getBottom() {#getBottom--}
```
public double getBottom()
```


Gets bottom vertical coordinate of visible rectangle.

**Returns:**
double
### getRight() {#getRight--}
```
public double getRight()
```


Gets right horizontal coordinate of visible rectangle.

**Returns:**
double
### getTop() {#getTop--}
```
public double getTop()
```


Gets top vertical coordinate of visible rectangle.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Converts the object state into string value. Example: "1 FitR 100 200 300 400".

**Returns:**
java.lang.String - String value representing object state.
