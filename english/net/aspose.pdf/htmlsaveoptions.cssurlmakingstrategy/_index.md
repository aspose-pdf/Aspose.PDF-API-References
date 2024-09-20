---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document. F.e. if You want to make CSS referenced in HTML f.e. as otherPage.ASPXCssIDzjjkklj Then such custom strategy must return otherPage.ASPXCssIDzjjkklj
type: docs
weight: 4000
url: /net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document. F.e. if You want to make CSS referenced in HTML f.e. as "otherPage.ASPX?CssID=zjjkklj" Then such custom strategy must return "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | represents set of data that can be used for generation of CSS' URL |

### Return Value

must return string that represents CSS's URL or URL's template

### See Also

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


