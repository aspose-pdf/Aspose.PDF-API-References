---
title: Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages method
linktitle: set_ExplicitListOfSavedPages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages method. With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown in C++.'
type: docs
weight: 3100
url: /cpp/aspose.pdf/htmlsaveoptions/set_explicitlistofsavedpages/
---
## HtmlSaveOptions::set_ExplicitListOfSavedPages method


With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown.

```cpp
void Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages(System::ArrayPtr<int32_t> value) override
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
