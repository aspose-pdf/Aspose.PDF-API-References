---
title: Aspose::Pdf::LoadOptions class
linktitle: LoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LoadOptions class. LoadOptions type holds level of abstraction on individual load options in C++.'
type: docs
weight: 10500
url: /cpp/aspose.pdf/loadoptions/
---
## LoadOptions class


[LoadOptions](./) type holds level of abstraction on individual load options.

```cpp
class LoadOptions : public virtual System::Object
```

## Nested classes

* Class [ResourceLoadingResult](./resourceloadingresult/)
## Enums

| Enum | Description |
| --- | --- |
| [MarginsAreaUsageModes](./marginsareausagemodes/) | Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins. |
| [PageSizeAdjustmentModes](./pagesizeadjustmentmodes/) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. |
## Methods

| Method | Description |
| --- | --- |
| [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Gets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [get_LoadFormat](./get_loadformat/)() const | Represents file format which [LoadOptions](./) describes. |
| [get_WarningHandler](./get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns [ReturnAction](../returnaction/) enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [LoadOptions](./loadoptions/)() |  |
| [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Sets flag to disable any license restrictions for all fonts while loading the file. When **true**

, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default **false**

. |
| [set_WarningHandler](./set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns [ReturnAction](../returnaction/) enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ResourceLoadingStrategy](./resourceloadingstrategy/) | Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of [Aspose.Pdf](../) in cloud direct access to referenced files impossible, and some custome code put into special method should be used. This delegate defines signature of such custom method. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
