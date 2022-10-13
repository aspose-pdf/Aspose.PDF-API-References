---
title: ExplicitDestinationType
second_title: Aspose.PDF for Java API Reference
description: Enumerates the types of explicit destinations.
type: docs
weight: 88
url: /java/com.aspose.pdf/explicitdestinationtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExplicitDestinationType extends System.Enum
```

Enumerates the types of explicit destinations.
## Fields

| Field | Description |
| --- | --- |
| [XYZ](#XYZ) | Display the page with the coordinates (left,\\ufffdtop) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. |
| [Fit](#Fit) | Display the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. |
| [FitH](#FitH) | Display the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. |
| [FitV](#FitV) | Display the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. |
| [FitR](#FitR) | Display the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. |
| [FitB](#FitB) | Display the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. |
| [FitBH](#FitBH) | Display the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. |
| [FitBV](#FitBV) | Display the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. |
### XYZ {#XYZ}
```
public static final int XYZ
```


Display the page with the coordinates (left,\\ufffdtop) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.

### Fit {#Fit}
```
public static final int Fit
```


Display the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the page within the window in the other dimension.

### FitH {#FitH}
```
public static final int FitH
```


Display the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.

### FitV {#FitV}
```
public static final int FitV
```


Display the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.

### FitR {#FitR}
```
public static final int FitR
```


Display the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.

### FitB {#FitB}
```
public static final int FitB
```


Display the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension.

### FitBH {#FitBH}
```
public static final int FitBH
```


Display the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.

### FitBV {#FitBV}
```
public static final int FitBV
```


Display the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.

