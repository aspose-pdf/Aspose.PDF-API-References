---
title: "类 GoToAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.GoToAction 类。表示一种 goto 操作，可将视图更改为指定的目标页面位置和放大系数。"
type: docs
weight: 1920
url: /zh/net/aspose.pdf.annotations/gotoaction/
---
## GoToAction class

表示跳转操作，可将视图更改为指定的目标（页面、位置和放大系数）。

```csharp
public class GoToAction : PdfAction
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | 构造函数。 |
| [GoToAction](gotoaction/#constructor_3)(Page) | GoToAction 类的构造函数。 |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | 与命名目标关联的操作。 |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | GoToAction 类的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | 获取或设置要跳转的目标。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 序列中的下一个操作。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | 获取 ECMAScript 操作的字符串。 |

### 另请参见

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


