---
title: Aspose::Pdf::HtmlSaveOptions::CustomHtmlSavingStrategy field
linktitle: CustomHtmlSavingStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::CustomHtmlSavingStrategy field. Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without exteranl linked files if any) that was created during conversion. In such case processing (like saving of paage''s HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter''s code itself, not in custom code, please set in custom code flag ''CustomProcessingCancelled'' of ''htmlSavingInfo'' parameter''s variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing  in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## CustomHtmlSavingStrategy field


Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without exteranl linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing .

```cpp
HtmlSaveOptions::HtmlPageMarkupSavingStrategy Aspose::Pdf::HtmlSaveOptions::CustomHtmlSavingStrategy
```

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
