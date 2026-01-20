---
title: Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages method
linktitle: get_SplitCssIntoPages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages method. When multipage-mode selected(i.e ''SplitIntoPages'' is ''true''), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue in C++.'
type: docs
weight: 2000
url: /cpp/aspose.pdf/htmlsaveoptions/get_splitcssintopages/
---
## HtmlSaveOptions::get_SplitCssIntoPages method


When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

```cpp
bool Aspose::Pdf::HtmlSaveOptions::get_SplitCssIntoPages() const
```

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
