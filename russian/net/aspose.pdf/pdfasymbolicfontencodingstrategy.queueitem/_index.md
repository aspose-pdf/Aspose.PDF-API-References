---
title: "Класс PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Указывает таблицу подшифрования. Каждая таблица подшифрования имеет уникальное сочетание параметров PlatformID PlatformSpecificId. Перечисление CMapEncodingTableType и свойство CMapEncodingTable были реализованы для упрощения создания необходимой таблицы подшифрования."
type: docs
weight: 8480
url: /ru/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem class

Указывает таблицу подшифрования. Каждая таблица подшифрования имеет уникальное сочетание параметров (PlatformID, PlatformSpecificId). Перечисление [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) и свойство [`CMapEncodingTable`](./cmapencodingtable/) были реализованы для упрощения создания необходимой таблицы подшифрования.

```csharp
public class QueueItem
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Конструктор, по умолчанию задает mac subtable(1,0) |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Конструктор |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Конструктор |

## Свойства

| Имя | Описание |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Указывает подтаблицу кодировки через перечисление [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Идентификатор платформы для подтаблицы кодировки |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Идентификатор кодировки, специфичный для платформы, для подтаблицы кодировки |

### См. также

* class [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


