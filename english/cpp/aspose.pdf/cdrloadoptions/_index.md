---
title: Aspose::Pdf::CdrLoadOptions class
linktitle: CdrLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CdrLoadOptions class. Class describes CDR load options in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf/cdrloadoptions/
---
## CdrLoadOptions class


Class describes CDR load options.

```cpp
class CdrLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [CdrLoadOptions](./cdrloadoptions/)() | Default constructor. |
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
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
