---
title: Aspose::Pdf::SvgLoadOptions class
linktitle: SvgLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SvgLoadOptions class. Represents options for loading/importing SVG file into pdf document in C++.'
type: docs
weight: 14400
url: /cpp/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class


Represents options for loading/importing SVG file into pdf document.

```cpp
class SvgLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_AdjustPageSize](./get_adjustpagesize/)() const | Adust pdf page size to svg size. |
| [get_DisableFontLicenseVerifications](../loadoptions/get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_LoadFormat](../loadoptions/get_loadformat/)() const | Represents file format which [LoadOptions](../loadoptions/) describes. |
| [get_PageInfo](./get_pageinfo/)() const | Gets page info that should be applied during loading of document. |
| [get_WarningHandler](../loadoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [LoadOptions](../loadoptions/loadoptions/)() |  |
| [set_AdjustPageSize](./set_adjustpagesize/)(bool) | Adust pdf page size to svg size. |
| [set_DisableFontLicenseVerifications](../loadoptions/set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_PageInfo](./set_pageinfo/)(System::SharedPtr\<Aspose::Pdf::PageInfo\>) | Sets page info that should be applied during loading of document. |
| [set_WarningHandler](../loadoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [SvgLoadOptions](./svgloadoptions/)() | Creates [SvgLoadOptions](./) object. |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
