---
title: Aspose::Pdf::SaveOptions class
linktitle: SaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::SaveOptions class. SaveOptions type hold level of abstraction on individual save options in C++.'
type: docs
weight: 14200
url: /cpp/aspose.pdf/saveoptions/
---
## SaveOptions class


[SaveOptions](./) type hold level of abstraction on individual save options.

```cpp
class SaveOptions : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_CacheGlyphs](./get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](./get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_SaveFormat](./get_saveformat/)() const | Format of data save. |
| [get_WarningHandler](./get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [set_CacheGlyphs](./set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](./set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_WarningHandler](./set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
