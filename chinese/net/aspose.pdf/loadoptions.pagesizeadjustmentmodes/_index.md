---
title: LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API 参考
description: 注意该功能已实现但尚未发布到公共 API因为 OSHARED 层中的阻止程序问题针对示例文档显示 表示转换期间页面大小的使用模式 格式如 HTMLEPUB 等通常具有浮动设计因此它允许适合 required pagesize但有时内容指定了 不允许将内容放入所需页面大小的水平位置或大小 在这种情况下我们可以定义在这种情况下应该做什么即当内容大小不适合 所需的初始页面大小时结果 PDF 文档.
type: docs
weight: 3970
url: /zh/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

注意！该功能已实现但尚未发布到公共 API，因为 OSHARED 层中的阻止程序问题针对示例文档显示。 表示转换期间页面大小的使用模式。 格式（如 HTML、EPUB 等），通常具有浮动设计，因此，它允许适合 required pagesize。但有时内容指定了 不允许将内容放入所需页面大小的水平位置或大小。 在这种情况下，我们可以定义在这种情况下应该做什么（即当内容大小不适合 所需的初始页面大小时结果 PDF 文档).

```csharp
public enum PageSizeAdjustmentModes
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | 在此模式下，结果页面将具有在 LoadOptions 中定义的所需页面大小， 无论转换后的内容是否超出页面边界。 |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | 此模式定义了这样的行为：在获得转换结果后， 并检测到某些内容已被截断， portview 的宽度被放大以适应内容并重复转换。 此模式允许获取更少的页面以导致这种情况但需要重复 渲染（因此需要更多处理时间）。 |

### 也可以看看

* class [LoadOptions](../loadoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
