---
title: Class GoToRemoteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.GoToRemoteAction 类。表示一种远程跳转动作，类似于普通的跳转动作，但跳转到另一个 PDF 文件中的目标，而不是当前文件
type: docs
weight: 1840
url: /zh/net/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class

表示一种远程跳转动作，类似于普通的跳转动作，但跳转到另一个 PDF 文件中的目标，而不是当前文件。

```csharp
public sealed class GoToRemoteAction : GoToAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToRemoteAction](gotoremoteaction/#constructor)(string, ExplicitDestination) | 初始化 GoToRemoteAction 对象。 |
| [GoToRemoteAction](gotoremoteaction/#constructor_1)(string, int) | 初始化 GoToRemoteAction 对象。 |

## Properties

| Name | Description |
| --- | --- |
| override [Destination](../../aspose.pdf.annotations/gotoremoteaction/destination/) { get; set; } | 获取或设置要跳转的目标。 |
| [File](../../aspose.pdf.annotations/gotoremoteaction/file/) { get; set; } | 获取或设置目标所在文件的规范。 |
| [NewWindow](../../aspose.pdf.annotations/gotoremoteaction/newwindow/) { get; set; } | 获取或设置一个标志，指示是否在新窗口中打开目标文档。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 顺序中的下一个动作。 |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | 获取 ECMAScript 动作的字符串。 |

### See Also

* class [GoToAction](../gotoaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)