---
title: HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API 参考
description: 您可以将实现处理的自定义策略分配给此属性 或/和保存在将 PDF 转换为 HTML 期间创建的一个 CSS 部分 在这种情况下处理如保存到流或磁盘 必须在该自定义中完成代码
type: docs
weight: 3460
url: /zh/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

您可以将实现处理的自定义策略分配给此属性 或/和保存在将 PDF 转换为 HTML 期间创建的一个 CSS 部分。 在这种情况下，处理（如保存到流或磁盘） 必须在该自定义中完成代码

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | 表示可用于保存提供的 CSS 部分的数据集 |

### 也可以看看

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo)
* class [HtmlSaveOptions](../htmlsaveoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->