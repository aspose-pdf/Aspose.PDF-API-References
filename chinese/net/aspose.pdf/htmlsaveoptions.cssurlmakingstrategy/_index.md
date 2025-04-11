---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 您可以将此属性委托分配给从自定义方法创建的委托，该方法实现生成的 HTML 文档中引用的 CSS 的 URL 的创建。例如，如果您想在 HTML 中引用 CSS，例如 "otherPage.ASPXCssIDzjjkklj"，那么这样的自定义策略必须返回 otherPage.ASPXCssIDzjjkklj
type: docs
weight: 5600
url: /zh/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy 委托

您可以将此属性委托分配给从自定义方法创建的委托，该方法实现生成的 HTML 文档中引用的 CSS 的 URL 的创建。例如，如果您想在 HTML 中引用 CSS，例如 "otherPage.ASPX?CssID=zjjkklj"，那么这样的自定义策略必须返回 "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | 表示可用于生成 CSS 的 URL 的数据集 |

### 返回值

必须返回表示 CSS 的 URL 或 URL 模板的字符串

### 另请参阅

* 类 [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* 类 [HtmlSaveOptions](../htmlsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)