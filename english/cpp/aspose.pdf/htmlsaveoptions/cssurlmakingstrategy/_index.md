---
title: Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy typedef
linktitle: CssUrlMakingStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy typedef. You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document. F.e. if You want to make CSS referenced in HTML f.e. as "otherPage.ASPX?CssID=zjjkklj" Then such custom strategy must return "otherPage.ASPX?CssID=zjjkklj" in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf/htmlsaveoptions/cssurlmakingstrategy/
---
## CssUrlMakingStrategy typedef


You can assign to this property delegate created from custom method that implements creation of URL of CSS referenced in generated HTML document. F.e. if You want to make CSS referenced in HTML f.e. as "otherPage.ASPX?CssID=zjjkklj" Then such custom strategy must return "otherPage.ASPX?CssID=zjjkklj".

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy =  System::MulticastDelegate<System::String(System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssUrlRequestInfo>)>
```


## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
