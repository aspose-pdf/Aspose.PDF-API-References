---
title: "FitExplicitDestination Class"
linktitle: "FitExplicitDestination"
articleTitle: "FitExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.FitExplicitDestination class. Represents explicit destination that displays the page with its contents magnified just enough to fit th..."
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
| [FitExplicitDestination](./fitexplicitdestination/#constructor)(int) | Creates remote explicit destination. |
| [FitExplicitDestination](./fitexplicitdestination/#constructor_1)(Page) | Creates local explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number |

## Methods

| Name | Description |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(Page, ExplicitDestinationType, params double[]) | Creates instances of ExplicitDestination descendant classes. |
| override [ToString](./tostring/)() | Converts the object state into string value. Example: "1 Fit". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

