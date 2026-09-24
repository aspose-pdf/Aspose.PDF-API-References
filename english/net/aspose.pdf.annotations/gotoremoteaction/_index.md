---
title: "GoToRemoteAction Class"
linktitle: "GoToRemoteAction"
articleTitle: "GoToRemoteAction"
second_title: "Aspose.PDF for .NET"
description: "Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file."
type: docs
weight: 460
url: "/net/aspose.pdf.annotations/gotoremoteaction/"
keywords: "GoToRemoteAction, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## GoToRemoteAction class

Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.

```csharp
public sealed class GoToRemoteAction : GoToAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToRemoteAction](./gotoremoteaction/#constructor)(*string, int*) | Initializes GoToRemoteAction object. |
| [GoToRemoteAction](./gotoremoteaction/#constructor_1)(*string, [ExplicitDestination](../../aspose.pdf.annotations/explicitdestination/)*) | Initializes GoToRemoteAction object. |

## Properties

| Name | Description |
| --- | --- |
| [Destination](./destination/) { get; set; } | Gets or sets the destination to jump to. |
| [File](./file/) { get; set; } | Gets or sets the specification of the file in which the destination is located. |
| [IsInitialized](../../aspose.pdf.annotations/pdfaction/isinitialized/) { get; } | Indicates whether the action has been initialized. *(Inherited from PdfAction)* |
| [NewWindow](./newwindow/) { get; set; } | Gets or sets a flag specifying whether to open the destination document in a new window. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Next actions in sequence. *(Inherited from PdfAction)* |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/) | Gets string for ECMAScript Action. *(Inherited from PdfAction)* |
| [ToString](../../aspose.pdf.annotations/iappointment/tostring/) | Returns string representation. *(Inherited from IAppointment)* |

### See Also

* class [GoToAction](../gotoaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

