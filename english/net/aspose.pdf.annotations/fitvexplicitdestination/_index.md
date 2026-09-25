---
title: "FitVExplicitDestination Class"
linktitle: "FitVExplicitDestination"
articleTitle: "FitVExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.FitVExplicitDestination class. Represents explicit destination that displays the page with the horizontal coordinate left positioned a..."
type: docs
weight: 410
url: "/net/aspose.pdf.annotations/fitvexplicitdestination/"
keywords: "FitVExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FitVExplicitDestination class

Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.

```csharp
public sealed class FitVExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitVExplicitDestination](./fitvexplicitdestination/#constructor)(*[Page](../../aspose.pdf/page/), double*) | Creates local explicit destination. |
| [FitVExplicitDestination](./fitvexplicitdestination/#constructor_1)(*int, double*) | Creates remote explicit destination. |
| [FitVExplicitDestination](./fitvexplicitdestination/#constructor_2)(*[Document](../../aspose.pdf/document/), int, double*) | Creates remote explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Left](./left/) { get; } | Gets the horizontal coordinate left positioned at the left edge of the window. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object. *(Inherited from ExplicitDestination)* |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number. *(Inherited from ExplicitDestination)* |

## Methods

| Name | Description |
| --- | --- |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Page, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Document, int, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [ToString](./tostring/) | Converts the object state into string value. Example: "1 FitV 100". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

