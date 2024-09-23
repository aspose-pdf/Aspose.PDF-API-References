---
title: Aspose::Pdf::HtmlSaveOptions::CustomStrategyOfCssUrlCreation field
linktitle: CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::CustomStrategyOfCssUrlCreation field. This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag ''SplitCssIntoPages'' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with string.Format() function inside converter) can be resolved into URL for this or that page''s CSS'' URL. Examples of expected return string in such case are: ''SomeTargetLocation-page_{0}.css'',''../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0}'') in C++.'
type: docs
weight: 5100
url: /cpp/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## CustomStrategyOfCssUrlCreation field


This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with string.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0}')

```cpp
HtmlSaveOptions::CssUrlMakingStrategy Aspose::Pdf::HtmlSaveOptions::CustomStrategyOfCssUrlCreation
```

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
