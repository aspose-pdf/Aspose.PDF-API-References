---
title: "XYZExplicitDestination Class"
linktitle: "XYZExplicitDestination"
articleTitle: "XYZExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination class. Represents explicit destination that displays the page with the coordinates (left, top) positioned at th..."
type: docs
weight: 1360
url: "/net/aspose.pdf.annotations/xyzexplicitdestination/"
keywords: "XYZExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## XYZExplicitDestination class

Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Examples

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

## Constructors

| Name | Description |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor)(Page, double, double, double) | Creates local explicit destination. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(int, double, double, double) | Creates remote explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Gets left horizontal coordinate of the upper-left corner of the window. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Gets top vertical coordinate of the upper-left corner of the window. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Gets zoom factor. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Create destintion to specified location of the page considering page rotation if required. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page, double) | Create destionation to upper left corner of the specifed page. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page) | Create destination to specified page. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Converts the object state into string value. Example: "1 XYZ 100 200 3". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

