---
title: "HtmlSaveOptions.CssUrlMakingStrategy Delegate"
linktitle: "HtmlSaveOptions.CssUrlMakingStrategy"
articleTitle: "HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Aspose.PDF for .NET API Reference"
description: "You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document. F.e. if You..."
type: docs
weight: 1230
url: "/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/"
product_version: "26.9.0"
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced 
 in generated HTML document. F.e. if You want to make CSS referenced in HTML f.e. as "otherPage.ASPX?CssID=zjjkklj"
 Then such custom strategy must return "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate void CssUrlMakingStrategy()
```

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

