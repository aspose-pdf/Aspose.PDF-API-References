---
title: FitRExplicitDestination
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.
type: docs
weight: 230
url: /python-net/aspose.pdf.annotations/fitrexplicitdestination/
---

## FitRExplicitDestination class

Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.

The FitRExplicitDestination type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FitRExplicitDestination(page, left, bottom, right, top)|Initializes a new instance of the FitRExplicitDestination class|
|FitRExplicitDestination(document, page_number, left, bottom, right, top)|Initializes a new instance of the FitRExplicitDestination class|
|FitRExplicitDestination(page_number, left, bottom, right, top)|Initializes a new instance of the FitRExplicitDestination class|
## Properties
| Name | Description |
| :- | :- |
|page|Gets the destination page object|
|page_number|Gets the destination page number|
|left|Gets left horizontal coordinate of visible rectangle.|
|bottom|Gets bottom vertical coordinate of visible rectangle.|
|right|Gets right horizontal coordinate of visible rectangle.|
|top|Gets top vertical coordinate of visible rectangle.|
## Methods
| Name | Description |
| :- | :- |
|create_destination(page, type, values)|Creates instances of ExplicitDestination descendant classes.|
|create_destination(doc, page_number, type, values)|Creates instances of ExplicitDestination descendant classes.|
|create_destination(page_number, type, values)|Creates instances of ExplicitDestination descendant classes.|
|to_string()|Converts the object state into string value. Example: "1 FitR 100 200 300 400".|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

