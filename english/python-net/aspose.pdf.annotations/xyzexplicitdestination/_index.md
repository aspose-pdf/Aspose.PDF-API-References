---
title: XYZExplicitDestination
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.
type: docs
weight: 880
url: /python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.

The XYZExplicitDestination type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|XYZExplicitDestination(page, left, top, zoom)|Initializes a new instance of the XYZExplicitDestination class|
|XYZExplicitDestination(document, page_number, left, top, zoom)|Initializes a new instance of the XYZExplicitDestination class|
|XYZExplicitDestination(page_number, left, top, zoom)|Initializes a new instance of the XYZExplicitDestination class|
## Properties
| Name | Description |
| :- | :- |
|page|Gets the destination page object|
|page_number|Gets the destination page number|
|left|Gets left horizontal coordinate of the upper-left corner of the window.|
|top|Gets top vertical coordinate of the upper-left corner of the window.|
|zoom|Gets zoom factor.|
## Methods
| Name | Description |
| :- | :- |
|create_destination(page, left, top, zoom, consider_rotation)|Create destintion to specified location of the page considering page rotation if required.|
|create_destination(page, type, values)|Creates instances of ExplicitDestination descendant classes.|
|create_destination(doc, page_number, type, values)|Creates instances of ExplicitDestination descendant classes.|
|create_destination(page_number, type, values)|Creates instances of ExplicitDestination descendant classes.|
|create_destination_to_upper_left_corner(page, zoom)|Create destionation to upper left corner of the specifed page.|
|create_destination_to_upper_left_corner(page)|Create destionation to upper left corner of the specifed page.|
|to_string()|Converts the object state into string value. Example: "1 XYZ 100 200 3".|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

