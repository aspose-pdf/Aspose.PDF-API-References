---
title: "FitExplicitDestination Class"
linktitle: "FitExplicitDestination"
articleTitle: "FitExplicitDestination"
second_title: "Aspose.PDF for .NET"
description: "Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and..."
type: docs
weight: 380
url: "/net/aspose.pdf.annotations/fitexplicitdestination/"
keywords: "FitExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FitExplicitDestination class

Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the page within the window in the other dimension.

```csharp
public sealed class FitExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitExplicitDestination](./fitexplicitdestination/#constructor)(*[Page](../../aspose.pdf/page/)*) | Creates local explicit destination. |
| [FitExplicitDestination](./fitexplicitdestination/#constructor_1)(*int*) | Creates remote explicit destination. |
| [FitExplicitDestination](./fitexplicitdestination/#constructor_2)(*[Document](../../aspose.pdf/document/), int*) | Creates remote explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object. *(Inherited from ExplicitDestination)* |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number. *(Inherited from ExplicitDestination)* |

## Methods

| Name | Description |
| --- | --- |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Page, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Document, int, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [GetNumber](../../aspose.pdf.annotations/explicitdestination/getnumber/)(*int*) | Gets double value by specified index of element. *(Inherited from ExplicitDestination)* |
| [ToString](./tostring/) | Converts the object state into string value. Example: "1 Fit". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

