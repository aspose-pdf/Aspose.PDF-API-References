---
title: "FitHExplicitDestination Class"
linktitle: "FitHExplicitDestination"
articleTitle: "FitHExplicitDestination"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.FitHExplicitDestination class. Represents explicit destination that displays the page with the vertical coordinate top positioned at t..."
type: docs
weight: 390
url: "/net/aspose.pdf.annotations/fithexplicitdestination/"
keywords: "FitHExplicitDestination, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FitHExplicitDestination class

Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.

```csharp
public sealed class FitHExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitHExplicitDestination](./fithexplicitdestination/#constructor)(*[Page](../../aspose.pdf/page/), double*) | Creates local explicit destination. |
| [FitHExplicitDestination](./fithexplicitdestination/#constructor_1)(*int, double*) | Creates remote explicit destination. |
| [FitHExplicitDestination](./fithexplicitdestination/#constructor_2)(*[Document](../../aspose.pdf/document/), int, double*) | Creates remote explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object. *(Inherited from ExplicitDestination)* |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number. *(Inherited from ExplicitDestination)* |
| [Top](./top/) { get; } | Gets the vertical coordinate top positioned at the top edge of the window. |

## Methods

| Name | Description |
| --- | --- |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Page, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [CreateDestination](../../aspose.pdf.annotations/explicitdestination/createdestination/)(*Document, int, ExplicitDestinationType, double[]*) | Creates instances of ExplicitDestination descendant classes. *(Inherited from ExplicitDestination)* |
| [GetNumber](../../aspose.pdf.annotations/explicitdestination/getnumber/)(*int*) | Gets double value by specified index of element. *(Inherited from ExplicitDestination)* |
| [ToString](./tostring/) | Converts the object state into string value. Example: "1 FitH 100". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

