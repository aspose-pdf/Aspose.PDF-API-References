---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FitRExplicitDestination class. Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left bottom right and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different use the smaller of the two centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior
type: docs
weight: 1870
url: /net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Constructors

| Name | Description |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | Creates remote explicit destination. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | Creates local explicit destination. |

## Properties

| Name | Description |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | Gets bottom vertical coordinate of visible rectangle. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | Gets left horizontal coordinate of visible rectangle. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Gets the destination page object |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Gets the destination page number |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Gets right horizontal coordinate of visible rectangle. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Gets top vertical coordinate of visible rectangle. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Converts the object state into string value. Example: "1 FitR 100 200 300 400". |

### See Also

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


