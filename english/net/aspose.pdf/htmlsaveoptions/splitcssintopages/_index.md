---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions property. When multipagemode selectedi.e SplitIntoPages is true then this attribute defines whether should be created separate CSSfile for each result HTML page. By default this attribute is false so will be created one big common CSS for all created pages. Summary size of all CSSes generated in this modeone CSS per page usually much more than size of one big CSS file because in former case CSS classes are duplicates in such case in several CSS files for each page. So this setting is worse to be used only when You are interested in future processing of each HTML page independently and therefore size of CSS of each one page taken apart is the most critical issue
type: docs
weight: 180
url: /net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### See Also

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


