---
title: "Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem class"
linktitle: "QueueItem"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem class. Указывает подтаблицу кодировки. Каждая подтаблица кодировки имеет уникальное сочетание параметров (PlatformID, PlatformSpecificId). Перечисление CMapEncodingTableType и свойство CMapEncodingTable были реализованы для упрощения выбора необходимой подтаблицы кодировки в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf/pdfasymbolicfontencodingstrategy/queueitem/
---
## QueueItem class


Указывает подтаблицу кодировки. Каждая подтаблица кодировки имеет уникальное сочетание параметров (PlatformID, PlatformSpecificId). Перечисление [CMapEncodingTableType](./cmapencodingtabletype/) и свойство [CMapEncodingTable](../) были реализованы для упрощения выбора необходимой подтаблицы кодировки.

```cpp
class QueueItem : public System::Object
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [CMapEncodingTableType](./cmapencodingtabletype/) | Объявляет набор некоторых известных подтаблиц кодировок. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_CMapEncodingTable](./get_cmapencodingtable/)() const | Указывает подтаблицу кодировки через перечисление [CMapEncodingTableType](./cmapencodingtabletype/). |
| [get_PlatformId](./get_platformid/)() const | Идентификатор платформы для подтаблицы кодировки. |
| [get_PlatformSpecificId](./get_platformspecificid/)() const | Идентификатор кодировки, специфичный для платформы, для подтаблицы кодировки. |
| [QueueItem](./queueitem/)() | Конструктор, по умолчанию указывает mac‑подтаблицу (1,0). |
| [QueueItem](./queueitem/)(uint16_t, uint16_t) | Конструктор. |
| [QueueItem](./queueitem/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Конструктор. |
| [set_CMapEncodingTable](./set_cmapencodingtable/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Указывает подтаблицу кодировки через перечисление [CMapEncodingTableType](./cmapencodingtabletype/). |
| [set_PlatformId](./set_platformid/)(uint16_t) | Идентификатор платформы для подтаблицы кодировки. |
| [set_PlatformSpecificId](./set_platformspecificid/)(uint16_t) | Идентификатор кодировки, специфичный для платформы, для подтаблицы кодировки. |
## См. также

* Class [Object](../../../system/object/)
* Class [PdfASymbolicFontEncodingStrategy](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
