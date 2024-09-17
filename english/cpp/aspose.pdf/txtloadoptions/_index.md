---
title: Aspose::Pdf::TxtLoadOptions class
linktitle: TxtLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TxtLoadOptions class. Load options for TXT to PDF conversion in C++.'
type: docs
weight: 15600
url: /cpp/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions class


Load options for TXT to PDF conversion.

```cpp
class TxtLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_DisableFontLicenseVerifications](../loadoptions/get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_LoadFormat](../loadoptions/get_loadformat/)() const | Represents file format which [LoadOptions](../loadoptions/) describes. |
| [get_WarningHandler](../loadoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [LoadOptions](../loadoptions/loadoptions/)() |  |
| [set_DisableFontLicenseVerifications](../loadoptions/set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_WarningHandler](../loadoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [TxtLoadOptions](./txtloadoptions/)() | Creates load options for converting text into pdf document. |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
