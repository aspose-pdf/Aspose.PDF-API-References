---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy class. Этот класс описывает правила, которые можно использовать для настройки процесса копирования данных кодировки для случаев, когда символьный шрифт TrueType имеет более одной кодировки.
type: docs
weight: 8330
url: /ru/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## Класс PdfASymbolicFontEncodingStrategy

Этот класс описывает правила, которые можно использовать для настройки процесса копирования данных кодировки для случаев, когда символьный шрифт TrueType имеет более одной кодировки. Некоторые PDF-документы после преобразования в формат PDF/A могут выдавать ошибку "More than one encoding in symbolic TrueType font's cmap". В чем причина данной ошибки? Все символьные шрифты TrueType содержат специальную таблицу "cmap" во внутренних данных. Эта таблица отображает коды символов на индексы глифов. И эта таблица может содержать различные подтаблицы кодировки, описывающие используемые кодировки. См. подробную информацию о таблицах cmap по адресу https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Обычно таблица cmap содержит несколько подтаблиц кодировки, но стандарт PDF/A требует, чтобы для этого шрифта в документе PDF/A оставалась только одна подтаблица кодировки или чтобы среди подтаблиц шрифта присутствовала подтаблица кодировки (3,0). И ключевой вопрос здесь – какие данные должны быть взяты из других подтаблиц для копирования в целевую таблицу кодировки (3,0)? Большинство шрифтов имеют "well-formed" таблицы cmap, где каждая подтаблица кодировки полностью согласована с другой подтаблицей. Но некоторые шрифты имеют таблицы cmap с коллизиями – где, например, одна подтаблица имеет индекс глифа 100 для юникода 100, а другая подтаблица имеет индекс глифа 200 для того же юникода 100. Для решения этой проблемы требуется особая стратегия. По умолчанию используется следующая стратегия: ищется подтаблица mac (1,0). Если эта таблица найдена, используются только её данные для заполнения целевой таблицы (3,0). Если подтаблица mac не найдена, то все подтаблицы, кроме (3,0), перебираются и используются для копирования данных в целевую подтаблицу (3,0). Также отображение для каждого юникода (юникод, индекс глифа) копируется в целевую таблицу только в том случае, если в целевой таблице на данный момент отсутствует этот юникод. Так, например, если первая подтаблица имеет индекс глифа 100 для юникода 100, а следующая подтаблица имеет индекс глифа 200 для того же юникода 100, то будут скопированы только данные из первой подтаблицы (unicode=100, glyph index = 100). Таким образом, каждая предыдущая подтаблица имеет приоритет над последующей. Свойства этого класса `PdfASymbolicFontEncodingStrategy` помогают настроить поведение по умолчанию. Если свойство [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) типа [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) установлено, то соответствующая подтаблица будет использована с приоритетом перед подтаблицей mac (1,0). Значение 'MacTable' из перечисления [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) в этом случае не имеет смысла, так как оно указывает на ту же подтаблицу mac (1,0), которая будет использоваться по умолчанию. Свойство [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) отменяет все приоритеты для любых подтаблиц. Если это свойство установлено, то будут использоваться только подтаблицы из объявленной очереди в указанном порядке. Если указанные подтаблицы не найдены, то будет применен стандартный перебор всех подтаблиц и стратегия копирования, описанная выше. Объект [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) определяет используемую подтаблицу кодировки. Эту подтаблицу можно задать посредством комбинации членов (PlatformID, PlatformSpecificId) или через перечисление [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/). В случае, если у шрифта отсутствует подтаблица (3,0), будет использована другая подтаблица для обеспечения совместимости с PDF/A. Выбор подтаблицы производится по тем же правилам, что описаны выше, поэтому свойства [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) и [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) используются для определения итоговой подтаблицы, и если у шрифта нет запрошенных подтаблиц, то будет использована любая существующая подтаблица.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## Конструкторы

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | Конструктор. Устанавливает подтаблицу по умолчанию (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | Конструктор |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | Конструктор |

## Свойства

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | Задает очередь подтаблиц кодировки для обработки. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | Задает подтаблицу, которая будет использоваться с приоритетом перед подтаблицей mac (1,0). Значение 'MacTable' из перечисления [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) в этом случае не имеет смысла. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)