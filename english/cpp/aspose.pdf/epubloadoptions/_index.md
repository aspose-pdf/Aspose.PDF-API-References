---
title: Aspose::Pdf::EpubLoadOptions class
linktitle: EpubLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::EpubLoadOptions class. Contains options for loading/importing EPUB file into pdf document in C++.'
type: docs
weight: 4000
url: /cpp/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class


Contains options for loading/importing EPUB file into pdf document.

```cpp
class EpubLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [EpubLoadOptions](./epubloadoptions/)() | Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](./epubloadoptions/)(System::Drawing::SizeF) | Creates load options with specified page size. |
| [get_CustomCss](./get_customcss/)() const | Gets the custom Css to apply when opening the Epub document. |
| [get_DisableFontLicenseVerifications](../loadoptions/get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_LoadFormat](../loadoptions/get_loadformat/)() const | Represents file format which [LoadOptions](../loadoptions/) describes. |
| [get_Margin](./get_margin/)() const | Gets reference on object that represent marging info. |
| [get_PageSize](./get_pagesize/)() const | Gets output page size for import. |
| [get_WarningHandler](../loadoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [LoadOptions](../loadoptions/loadoptions/)() |  |
| [set_CustomCss](./set_customcss/)(System::String) | Sets the custom Css to apply when opening the Epub document. |
| [set_DisableFontLicenseVerifications](../loadoptions/set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_Margin](./set_margin/)(System::SharedPtr\<MarginInfo\>) | Gets reference on object that represent marging info. |
| [set_WarningHandler](../loadoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
