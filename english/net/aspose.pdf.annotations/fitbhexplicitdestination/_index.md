---
title: "FitBHExplicitDestination Class"
linktitle: "FitBHExplicitDestination"
articleTitle: "FitBHExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.FitBHExplicitDestination class. Represents explicit destination that displays the page with the vertical coordinate top positioned at ..."
type: docs
weight: 360
url: "/net/aspose.pdf.annotations/fitbhexplicitdestination/"
keywords: "FitBHExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FitBHExplicitDestination class

Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.

```csharp
public sealed class FitBHExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitBHExplicitDestination](./fitbhexplicitdestination/#constructor)(int, double) | Creates remote explicit destination. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/#constructor_1)(Page, double) | Creates local explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number |
| [Top](./top/) { get; } | Gets the vertical coordinate top positioned at the top edge of the window. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(Page, ExplicitDestinationType, params double[]) | Creates instances of ExplicitDestination descendant classes. |
| override [ToString](./tostring/)() | Converts the object state into string value. Example: "1 FitBH 100". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

