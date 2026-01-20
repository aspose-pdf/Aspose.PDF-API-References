---
title: Aspose::Pdf::Annotations::ExplicitDestinationType enum
linktitle: ExplicitDestinationType
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::ExplicitDestinationType enum. Enumerates the types of explicit destinations in C++.'
type: docs
weight: 13100
url: /cpp/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enum


Enumerates the types of explicit destinations.

```cpp
enum class ExplicitDestinationType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| XYZ | 0 | Display the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value. |
| Fit | 1 | Display the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the page within the window in the other dimension. |
| FitH | 2 | Display the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged. |
| FitV | 3 | Display the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged. |
| FitR | 4 | Display the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior. |
| FitB | 5 | Display the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension. |
| FitBH | 6 | Display the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged. |
| FitBV | 7 | Display the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged. |

## See Also

* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
