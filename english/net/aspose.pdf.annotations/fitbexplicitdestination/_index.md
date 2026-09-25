---
title: "FitBExplicitDestination Class"
linktitle: "FitBExplicitDestination"
articleTitle: "FitBExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.FitBExplicitDestination class. Represents explicit destination that displays the page with its contents magnified just enough to fit i..."
type: docs
weight: 350
url: "/net/aspose.pdf.annotations/fitbexplicitdestination/"
keywords: "FitBExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FitBExplicitDestination class

Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension.

```csharp
public sealed class FitBExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitBExplicitDestination](./fitbexplicitdestination/#constructor)(*[Page](../../aspose.pdf/page/)*) | Creates local explicit destination. |
| [FitBExplicitDestination](./fitbexplicitdestination/#constructor_1)(*int*) | Creates remote explicit destination. |
| [FitBExplicitDestination](./fitbexplicitdestination/#constructor_2)(*[Document](../../aspose.pdf/document/), int*) | Creates remote explicit destination. |

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
| [ToString](./tostring/) | Converts the object state into string value. Example: "1 FitB". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

