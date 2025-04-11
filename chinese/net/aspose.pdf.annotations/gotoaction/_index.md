---
title: Class GoToAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.GoToAction 类。表示一个跳转动作，该动作将视图更改为指定的目标页面位置和放大倍数
type: docs
weight: 1830
url: /zh/net/aspose.pdf.annotations/gotoaction/
---
## GoToAction class

表示一个跳转动作，该动作将视图更改为指定的目标（页面、位置和放大倍数）。

```csharp
public class GoToAction : PdfAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | 构造函数。 |
| [GoToAction](gotoaction/#constructor_3)(Page) | GoToAction 类的构造函数。 |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | 与命名目标链接的动作。 |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | GoToAction 类的构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | 获取或设置要跳转的目标。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 顺序中的下一个动作。 |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | 获取 ECMAScript 动作的字符串。 |

### See Also

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)