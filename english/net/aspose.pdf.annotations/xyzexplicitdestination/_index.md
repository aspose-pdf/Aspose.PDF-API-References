---
title: "XYZExplicitDestination Class"
linktitle: "XYZExplicitDestination"
articleTitle: "XYZExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination class. Represents explicit destination that displays the page with the coordinates (left, top) positioned at th..."
type: docs
weight: 1370
url: "/net/aspose.pdf.annotations/xyzexplicitdestination/"
keywords: "XYZExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XYZExplicitDestination class

Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [XYZExplicitDestination](./xyzexplicitdestination/#constructor)(*[Page](../../aspose.pdf/page/), double, double, double*) | Creates local explicit destination. |
| [XYZExplicitDestination](./xyzexplicitdestination/#constructor_1)(*int, double, double, double*) | Creates remote explicit destination. |
| [XYZExplicitDestination](./xyzexplicitdestination/#constructor_2)(*[Document](../../aspose.pdf/document/), int, double, double, double*) | Creates remote explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Left](./left/) { get; } | Gets left horizontal coordinate of the upper-left corner of the window. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object. *(Inherited from ExplicitDestination)* |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number. *(Inherited from ExplicitDestination)* |
| [Top](./top/) { get; } | Gets top vertical coordinate of the upper-left corner of the window. |
| [Zoom](./zoom/) { get; } | Gets zoom factor. |

## Methods

| Name | Description |
| --- | --- |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Page, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Document, int, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [CreateDestination](./createdestination/)(*Page, double, double, double, bool*) | Create destintion to specified location of the page considering page rotation if required. |
| [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(*Page*) | Create destination to specified page. |
| [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(*Page, double*) | Create destionation to upper left corner of the specifed page. |
| [GetNumber](../../aspose.pdf.annotations/explicitdestination/getnumber/)(*int*) | Gets double value by specified index of element. *(Inherited from ExplicitDestination)* |
| [ToString](./tostring/) | Converts the object state into string value. Example: "1 XYZ 100 200 3". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

