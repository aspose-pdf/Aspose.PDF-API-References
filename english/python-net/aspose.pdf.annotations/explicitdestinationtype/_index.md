---
title: ExplicitDestinationType
second_title: Aspose.PDF for Python via .NET API Reference
description: Enumerates the types of explicit destinations.
type: docs
weight: 1020
url: /python-net/aspose.pdf.annotations/explicitdestinationtype/
---

## ExplicitDestinationType enumeration

Enumerates the types of explicit destinations.

## Members
| Member name | Description |
| :- | :- |
|XYZ|Display the page with the coordinates (left,�top) positioned at the upper-left corner of the window<br/>            and the contents of the page magnified by the factor zoom. A null value for any of the parameters<br/>            left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. <br/>            A zoom value of 0 has the same meaning as a null value.|
|FIT|Display the page with its contents magnified just enough to fit the entire page within the window<br/>            both horizontally and vertically. If the required horizontal and vertical magnification factors are<br/>            different, use the smaller of the two, centering the page within the window in the other dimension.|
|FIT_H|Display the page with the vertical coordinate top positioned at the top edge of the window and<br/>            the contents of the page magnified just enough to fit the entire width of the page within the window.<br/>            A null value for top specifies that the current value of that parameter is to be retained unchanged.|
|FIT_V|Display the page with the horizontal coordinate left positioned at the left edge of the window<br/>            and the contents of the page magnified just enough to fit the entire height of the page within the window.<br/>            A null value for left specifies that the current value of that parameter is to be retained unchanged.|
|FIT_R|Display the page with its contents magnified just enough to fit the rectangle specified by the<br/>            coordinates left, bottom, right, and topentirely within the window both horizontally and vertically.<br/>            If the required horizontal and vertical magnification factors are different, use the smaller of<br/>            the two, centering the rectangle within the window in the other dimension. A null value for any<br/>            of the parameters may result in unpredictable behavior.|
|FIT_B|Display the page with its contents magnified just enough to fit its bounding box entirely within<br/>            the window both horizontally and vertically. If the required horizontal and vertical magnification<br/>            factors are different, use the smaller of the two, centering the bounding box within the window<br/>            in the other dimension.|
|FIT_BH|Display the page with the vertical coordinate top positioned at the top edge of the window and the<br/>            contents of the page magnified just enough to fit the entire width of its bounding box within the window.<br/>            A null value for top specifies that the current value of that parameter is to be retained unchanged.|
|FIT_BV|Display the page with the horizontal coordinate left positioned at the left edge of the window and the<br/>            contents of the page magnified just enough to fit the entire height of its bounding box within the window.<br/>            A null value for left specifies that the current value of that parameter is to be retained unchanged.|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

