---
title: "FitBVExplicitDestination Class"
linktitle: "FitBVExplicitDestination"
articleTitle: "FitBVExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.FitBVExplicitDestination class. Represents explicit destination that displays the page with the horizontal coordinate left positioned ..."
type: docs
weight: 370
url: "/net/aspose.pdf.annotations/fitbvexplicitdestination/"
keywords: "FitBVExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FitBVExplicitDestination class

Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.

```csharp
public sealed class FitBVExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitBVExplicitDestination](./fitbvexplicitdestination/#constructor)(int, double) | Creates remote explicit destination. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/#constructor_1)(Page, double) | Creates local explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Left](./left/) { get; } | Gets the horizontal coordinate left positioned at the left edge of the window. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number |

## Methods

| Name | Description |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(Page, ExplicitDestinationType, params double[]) | Creates instances of ExplicitDestination descendant classes. |
| override [ToString](./tostring/)() | Converts the object state into string value. Example: "1 FitBV 100". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

