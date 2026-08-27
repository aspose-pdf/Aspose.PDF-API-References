---
title: "委托 HtmlSaveOptions.CssSavingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "您可以为此属性分配自定义策略，该策略实现对在 PDF 转换为 HTML 期间创建的某个 CSS 部分的处理或/以及保存。在这种情况下，诸如保存到流或磁盘的处理必须在该自定义代码中完成。"
type: docs
weight: 5720
url: /zh/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

您可以为此属性分配自定义策略，该策略实现对在 PDF 转换为 HTML 期间创建的某个 CSS 部分的处理或/以及保存。在这种情况下，处理（如保存到流或磁盘）必须在该自定义代码中完成。

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | 表示一组可用于保存提供的 CSS 部分的数据 |

### 另请参见

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


