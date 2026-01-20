---
title: Aspose::Pdf::HtmlSaveOptions::set_SplitCssIntoPages method
linktitle: set_SplitCssIntoPages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::set_SplitCssIntoPages method. When multipage-mode selected(i.e ''SplitIntoPages'' is ''true''), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue in C++.'
type: docs
weight: 4200
url: /cpp/aspose.pdf/htmlsaveoptions/set_splitcssintopages/
---
## HtmlSaveOptions::set_SplitCssIntoPages method


When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

```cpp
void Aspose::Pdf::HtmlSaveOptions::set_SplitCssIntoPages(bool value)
```

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
