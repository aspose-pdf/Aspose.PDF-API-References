---
title: Class GoToRemoteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.GoToRemoteAction class. Represents a remote goto action that is similar to an ordinary goto action but jumps to a destination in another PDF file instead of the current file
type: docs
weight: 490
url: /net/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class

Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.

```csharp
public sealed class GoToRemoteAction : GoToAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToRemoteAction](gotoremoteaction/#constructor)(string, ExplicitDestination) | Initializes GoToRemoteAction object. |
| [GoToRemoteAction](gotoremoteaction/#constructor_1)(string, int) | Initializes GoToRemoteAction object. |

## Properties

| Name | Description |
| --- | --- |
| override [Destination](../../aspose.pdf.annotations/gotoremoteaction/destination/) { get; set; } | Gets or sets the destination to jump to. |
| [File](../../aspose.pdf.annotations/gotoremoteaction/file/) { get; set; } | Gets or sets the specification of the file in which the destination is located. |
| [NewWindow](../../aspose.pdf.annotations/gotoremoteaction/newwindow/) { get; set; } | Gets or sets a flag specifying whether to open the destination document in a new window. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Next actions in sequence. |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Gets string for ECMAScript Action. |

### See Also

* class [GoToAction](../gotoaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


