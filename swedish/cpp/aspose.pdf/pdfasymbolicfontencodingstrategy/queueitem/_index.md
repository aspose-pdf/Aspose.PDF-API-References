---
title: "Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem klass"
linktitle: "QueueItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem klass. Anger kodningssubtabell. Varje kodningssubtabell har en unik kombination av parametrar (PlatformID, PlatformSpecificId). Uppräkning CMapEncodingTableType och egenskap CMapEncodingTable implementerades för att underlätta att ange kodningssubtabell som behövs i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.pdf/pdfasymbolicfontencodingstrategy/queueitem/
---
## QueueItem class


Anger kodningssubtabell. Varje kodningssubtabell har en unik kombination av parametrar (PlatformID, PlatformSpecificId). Uppräkning [CMapEncodingTableType](./cmapencodingtabletype/) och egenskap [CMapEncodingTable](../) implementerades för att underlätta att ange kodningssubtabell som behövs.

```cpp
class QueueItem : public System::Object
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [CMapEncodingTableType](./cmapencodingtabletype/) | Deklarerar en uppsättning av några kända kodningssubtabeller. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CMapEncodingTable](./get_cmapencodingtable/)() const | Anger kodningens deltabell via [CMapEncodingTableType](./cmapencodingtabletype/)enumeration. |
| [get_PlatformId](./get_platformid/)() const | Plattformsidentifierare för kodningens deltabell. |
| [get_PlatformSpecificId](./get_platformspecificid/)() const | Plattformspecifik kodningsidentifierare för kodningens deltabell. |
| [QueueItem](./queueitem/)() | Konstruktor, anger mac-deltabell(1,0) som standard. |
| [QueueItem](./queueitem/)(uint16_t, uint16_t) | Konstruktor. |
| [QueueItem](./queueitem/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Konstruktor. |
| [set_CMapEncodingTable](./set_cmapencodingtable/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Anger kodningens deltabell via [CMapEncodingTableType](./cmapencodingtabletype/)enumeration. |
| [set_PlatformId](./set_platformid/)(uint16_t) | Plattformsidentifierare för kodningens deltabell. |
| [set_PlatformSpecificId](./set_platformspecificid/)(uint16_t) | Plattformspecifik kodningsidentifierare för kodningens deltabell. |
## Se även

* Class [Object](../../../system/object/)
* Class [PdfASymbolicFontEncodingStrategy](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
