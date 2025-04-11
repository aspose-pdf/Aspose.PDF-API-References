---
title: Class XForm
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XForm class. Class represent XForm
type: docs
weight: 11330
url: /zh/net/aspose.pdf/xform/
---
## XForm class

类表示 XForm

```csharp
public sealed class XForm : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [BBox](../../aspose.pdf/xform/bbox/) { get; set; } | 获取或设置表单边界框。 |
| [Contents](../../aspose.pdf/xform/contents/) { get; } | 获取表单的操作符。 |
| [IT](../../aspose.pdf/xform/it/) { get; } | 获取表单 IT。表单 IT 是描述 XObject 意图的名称。 |
| [Matrix](../../aspose.pdf/xform/matrix/) { get; set; } | 获取或设置表单的矩阵。 |
| [Name](../../aspose.pdf/xform/name/) { get; set; } | 获取或设置表单名称。表单名称是用于在页面资源的 XObject 字典中引用表单的名称。 |
| [Opi](../../aspose.pdf/xform/opi/) { get; } | 获取开放印前接口 (OPI)。 |
| [Rectangle](../../aspose.pdf/xform/rectangle/) { get; } | 获取或设置表单的矩形。 |
| [Resources](../../aspose.pdf/xform/resources/) { get; } | 获取表单 XObject 资源。 |
| [Subtype](../../aspose.pdf/xform/subtype/) { get; } | 获取表单子类型。 |

## Methods

| Name | Description |
| --- | --- |
| static [CreateNewForm](../../aspose.pdf/xform/createnewform/)(Page, Document) | 创建一个 XForm，该 XForm 复制页面的内容。 |
| [Dispose](../../aspose.pdf/xform/dispose/)() | 释放内存 |
| [FreeMemory](../../aspose.pdf/xform/freememory/)() | 清除缓存数据 |
| [GetResources](../../aspose.pdf/xform/getresources/#getresources)() | 返回表单 X-Object 的资源。如果表单没有资源并且 allowCreate 为 true，则将自动为表单创建资源。 |
| [GetResources](../../aspose.pdf/xform/getresources/#getresources_1)(bool) | 返回表单 X-Object 的资源 |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)