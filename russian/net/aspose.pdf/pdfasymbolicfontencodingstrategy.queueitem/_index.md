---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Указывает подтаблицу кодирования. Каждая подтаблица кодирования имеет уникальное сочетание параметров PlatformID, PlatformSpecificId. Перечисление [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) и свойство [`CMapEncodingTable`](./cmapencodingtable/) были реализованы для упрощения установки необходимой подтаблицы кодирования.
type: docs
weight: 8340
url: /ru/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## Класс PdfASymbolicFontEncodingStrategy.QueueItem

Указывает подтаблицу кодирования. Каждая подтаблица кодирования имеет уникальное сочетание параметров (PlatformID, PlatformSpecificId). Перечисление [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) и свойство [`CMapEncodingTable`](./cmapencodingtable/) были реализованы для упрощения установки необходимой подтаблицы кодирования.

```csharp
public class QueueItem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Конструктор, по умолчанию указывает mac подтаблицу(1,0) |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Конструктор |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Конструктор |

## Свойства

| Имя | Описание |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Указывает подтаблицу кодирования через перечисление [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Идентификатор платформы для подтаблицы кодирования |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Идентификатор кодирования, специфичный для платформы, для подтаблицы кодирования |

### См. также

* класс [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)