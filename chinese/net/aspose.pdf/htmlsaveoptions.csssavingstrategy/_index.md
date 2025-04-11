---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 您可以为此属性分配自定义策略，该策略实现了在将 PDF 转换为 HTML 过程中创建的一个 CSS 部分的处理和/或保存。在这种情况下，处理（如保存到流或磁盘）必须在该自定义代码中完成
type: docs
weight: 5590
url: /zh/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy 委托

您可以为此属性分配自定义策略，该策略实现了在将 PDF 转换为 HTML 过程中创建的一个 CSS 部分的处理和/或保存。在这种情况下，处理（如保存到流或磁盘）必须在该自定义代码中完成

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | 表示可以用于保存提供的 CSS 部分的数据集 |

### 另请参阅

* 类 [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* 类 [HtmlSaveOptions](../htmlsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)