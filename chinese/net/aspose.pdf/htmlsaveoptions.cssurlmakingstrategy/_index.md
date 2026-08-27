---
title: "委托 HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "您可以将此属性分配为由自定义方法创建的委托，该方法实现生成的 HTML 文档中引用的 CSS 的 URL。比如，如果您想在 HTML 中引用 CSS，例如 otherPage.ASPXCssIDzjjkklj，则此自定义策略必须返回 otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5730
url: /zh/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

您可以将此属性分配为由自定义方法创建的委托，该方法实现生成的 HTML 文档中引用的 CSS 的 URL。比如，如果您想在 HTML 中引用 CSS，例如 \"otherPage.ASPX?CssID=zjjkklj\"，则此自定义策略必须返回 \"otherPage.ASPX?CssID=zjjkklj\"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | 表示一组可用于生成 CSS URL 的数据 |

### 返回值

必须返回表示 CSS URL 或 URL 模板的字符串

### 另请参见

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


