---
title: "FitRExplicitDestination Class"
linktitle: "FitRExplicitDestination"
articleTitle: "FitRExplicitDestination"
second_title: "Aspose.PDF for .NET"
description: "Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom..."
type: docs
weight: 400
url: "/net/aspose.pdf.annotations/fitrexplicitdestination/"
keywords: "FitRExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FitRExplicitDestination class

Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitRExplicitDestination](./fitrexplicitdestination/#constructor)(*[Page](../../aspose.pdf/page/), double, double, double, double*) | Creates local explicit destination. |
| [FitRExplicitDestination](./fitrexplicitdestination/#constructor_1)(*int, double, double, double, double*) | Creates remote explicit destination. |
| [FitRExplicitDestination](./fitrexplicitdestination/#constructor_2)(*[Document](../../aspose.pdf/document/), int, double, double, double, double*) | Creates remote explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Bottom](./bottom/) { get; } | Gets bottom vertical coordinate of visible rectangle. |
| [Left](./left/) { get; } | Gets left horizontal coordinate of visible rectangle. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object. *(Inherited from ExplicitDestination)* |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number. *(Inherited from ExplicitDestination)* |
| [Right](./right/) { get; } | Gets right horizontal coordinate of visible rectangle. |
| [Top](./top/) { get; } | Gets top vertical coordinate of visible rectangle. |

## Methods

| Name | Description |
| --- | --- |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Page, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Document, int, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [GetNumber](../../aspose.pdf.annotations/explicitdestination/getnumber/)(*int*) | Gets double value by specified index of element. *(Inherited from ExplicitDestination)* |
| [ToString](./tostring/) | Converts the object state into string value. Example: "1 FitR 100 200 300 400". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

