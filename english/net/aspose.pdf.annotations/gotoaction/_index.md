---
title: "GoToAction Class"
linktitle: "GoToAction"
articleTitle: "GoToAction"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.GoToAction class. Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor)."
type: docs
weight: 450
url: "/net/aspose.pdf.annotations/gotoaction/"
keywords: "GoToAction, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## GoToAction class

Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor).

```csharp
public class GoToAction : PdfAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToAction](./gotoaction/#constructor)(ExplicitDestination) | Constructor. |
| [GoToAction](./gotoaction/#constructor_1)(Page) | Constructor for GoToAction class. |
| [GoToAction](./gotoaction/#constructor_2)(Document, string) | Action which linked with Named Destination. |
| [GoToAction](./gotoaction/#constructor_3)(Page, ExplicitDestinationType, params double[]) | Constructor for GoToAction class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Destination](./destination/) { get; set; } | Gets or sets the destination to jump to. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Next actions in sequence. |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Gets string for ECMAScript Action. |
| [ToString](../../aspose.pdf.annotations/iappointment/tostring/)() | Returns string representation |

### See Also

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

