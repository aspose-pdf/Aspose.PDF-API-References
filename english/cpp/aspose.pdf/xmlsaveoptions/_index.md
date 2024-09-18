---
title: Aspose::Pdf::XmlSaveOptions class
linktitle: XmlSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XmlSaveOptions class. Save options for export to Xml format in C++.'
type: docs
weight: 16800
url: /cpp/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions class


Save options for export to Xml format.

```cpp
class XmlSaveOptions : public Aspose::Pdf::SaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_CacheGlyphs](../saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_SaveFormat](../saveoptions/get_saveformat/)() const | Format of data save. |
| [get_WarningHandler](../saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [set_CacheGlyphs](../saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_WarningHandler](../saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [XmlSaveOptions](./xmlsaveoptions/)() | Constructor. |
## See Also

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
