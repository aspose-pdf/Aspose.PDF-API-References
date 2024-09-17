---
title: Aspose::Pdf::HtmlLoadOptions class
linktitle: HtmlLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlLoadOptions class. Represents options for loading/importing html file into pdf document in C++.'
type: docs
weight: 5700
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
| [get_DisableFontLicenseVerifications](../loadoptions/get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_HtmlMediaType](./get_htmlmediatype/)() const | Gets possible media types used during rendering. |
| [get_InputEncoding](./get_inputencoding/)() const | Gets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute. |
| [get_IsEmbedFonts](./get_isembedfonts/)() const | Gets fonts embedding to result document. |
| [get_IsPriorityCssPageRule](./get_isprioritycsspagerule/)() const |  |
| [get_IsRenderToSinglePage](./get_isrendertosinglepage/)() const | Gets rendering all document to single page. |
| [get_LoadFormat](../loadoptions/get_loadformat/)() const | Represents file format which [LoadOptions](../loadoptions/) describes. |
| [get_PageInfo](./get_pageinfo/)() const | Gets document page info. |
| [get_PageLayoutOption](./get_pagelayoutoption/)() const | Gets layout option. |
| [get_WarningHandler](../loadoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [HtmlLoadOptions](./htmlloadoptions/)() | Creates load options for converting html into pdf document with empty base path. |
| [HtmlLoadOptions](./htmlloadoptions/)(System::String) | Creates load options for converting html into pdf document with defined base path. |
| [LoadOptions](../loadoptions/loadoptions/)() |  |
| [set_DisableFontLicenseVerifications](../loadoptions/set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_HtmlMediaType](./set_htmlmediatype/)(Aspose::Pdf::HtmlMediaType) | Sets possible media types used during rendering. |
| [set_InputEncoding](./set_inputencoding/)(System::String) | Sets the attribute specifying the encoding used for this document at the time of the parsing. If this attribute is null the encoding will determine from document character set atribute. |
| [set_IsEmbedFonts](./set_isembedfonts/)(bool) | Sets fonts embedding to result document. |
| [set_IsPriorityCssPageRule](./set_isprioritycsspagerule/)(bool) |  |
| [set_IsRenderToSinglePage](./set_isrendertosinglepage/)(bool) | Sets rendering all document to single page. |
| [set_PageInfo](./set_pageinfo/)(System::SharedPtr\<Aspose::Pdf::PageInfo\>) | Sets document page info. |
| [set_PageLayoutOption](./set_pagelayoutoption/)(HtmlPageLayoutOption) | Sets layout option. |
| [set_WarningHandler](../loadoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
