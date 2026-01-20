---
title: Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem class
linktitle: QueueItem
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem class. Specifies encoding subtable. Each encoding subtable has unique combination of parameters (PlatformID, PlatformSpecificId). Enumeration CMapEncodingTableType and property CMapEncodingTable were implemented to make easier set of encoding subtable needed in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/pdfasymbolicfontencodingstrategy/queueitem/
---
## QueueItem class


Specifies encoding subtable. Each encoding subtable has unique combination of parameters (PlatformID, PlatformSpecificId). Enumeration [CMapEncodingTableType](./cmapencodingtabletype/) and property [CMapEncodingTable](../) were implemented to make easier set of encoding subtable needed.

```cpp
class QueueItem : public System::Object
```

## Enums

| Enum | Description |
| --- | --- |
| [CMapEncodingTableType](./cmapencodingtabletype/) | Declares set of some known encoding subtables. |
## Methods

| Method | Description |
| --- | --- |
| [get_CMapEncodingTable](./get_cmapencodingtable/)() const | Specifies encoding subtable via [CMapEncodingTableType](./cmapencodingtabletype/)enumeration. |
| [get_PlatformId](./get_platformid/)() const | Platform identifier for encoding subtable. |
| [get_PlatformSpecificId](./get_platformspecificid/)() const | Platform-specific encoding identifier for encoding subtable. |
| [QueueItem](./queueitem/)() | Constructor, specifies mac subtable(1,0) by default. |
| [QueueItem](./queueitem/)(uint16_t, uint16_t) | Constructor. |
| [QueueItem](./queueitem/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Constructor. |
| [set_CMapEncodingTable](./set_cmapencodingtable/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Specifies encoding subtable via [CMapEncodingTableType](./cmapencodingtabletype/)enumeration. |
| [set_PlatformId](./set_platformid/)(uint16_t) | Platform identifier for encoding subtable. |
| [set_PlatformSpecificId](./set_platformspecificid/)(uint16_t) | Platform-specific encoding identifier for encoding subtable. |
## See Also

* Class [Object](../../../system/object/)
* Class [PdfASymbolicFontEncodingStrategy](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
