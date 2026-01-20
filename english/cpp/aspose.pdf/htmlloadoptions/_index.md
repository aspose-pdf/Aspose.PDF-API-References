---
title: Aspose::Pdf::HtmlLoadOptions class
linktitle: HtmlLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlLoadOptions class. Represents options for loading/importing html file into pdf document in C++.'
type: docs
weight: 7200
url: /cpp/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class


Represents options for loading/importing html file into pdf document.

```cpp
class HtmlLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | The base path/url for the html file. |
| [get_CreateLogicalStructure](./get_createlogicalstructure/)() const | Gets a value indicating whether to create a logical structure in the resulting PDF document. |
| [get_HtmlMediaType](./get_htmlmediatype/)() const | Gets possible media types used during rendering. |
| [get_InputEncoding](./get_inputencoding/)() const | Gets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute. |
| [get_IsEmbedFonts](./get_isembedfonts/)() const | Gets fonts embedding to result document. |
| [get_IsPriorityCssPageRule](./get_isprioritycsspagerule/)() const |  |
| [get_IsRenderToSinglePage](./get_isrendertosinglepage/)() const | Gets rendering all document to single page. |
| [get_PageInfo](./get_pageinfo/)() const | Gets document page info. |
| [get_PageLayoutOption](./get_pagelayoutoption/)() const | Gets layout option. |
| [HtmlLoadOptions](./htmlloadoptions/)() | Creates load options for converting html into pdf document with empty base path. |
| [HtmlLoadOptions](./htmlloadoptions/)(System::String) | Creates load options for converting html into pdf document with defined base path. |
| [set_CreateLogicalStructure](./set_createlogicalstructure/)(bool) | Sets a value indicating whether to create a logical structure in the resulting PDF document. |
| [set_HtmlMediaType](./set_htmlmediatype/)(Aspose::Pdf::HtmlMediaType) | Sets possible media types used during rendering. |
| [set_InputEncoding](./set_inputencoding/)(System::String) | Sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute. |
| [set_IsEmbedFonts](./set_isembedfonts/)(bool) | Sets fonts embedding to result document. |
| [set_IsPriorityCssPageRule](./set_isprioritycsspagerule/)(bool) |  |
| [set_IsRenderToSinglePage](./set_isrendertosinglepage/)(bool) | Sets rendering all document to single page. |
| [set_PageInfo](./set_pageinfo/)(System::SharedPtr\<Aspose::Pdf::PageInfo\>) | Sets document page info. |
| [set_PageLayoutOption](./set_pagelayoutoption/)(HtmlPageLayoutOption) | Sets layout option. |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
