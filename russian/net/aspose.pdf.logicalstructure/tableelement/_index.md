---
title: TableElement
second_title: Aspose.PDF для справочника API .NET
description: Представляет элемент структуры таблицы в логической структуре.
type: docs
weight: 4610
url: /ru/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Представляет элемент структуры таблицы в логической структуре.

```csharp
public sealed class TableElement : BLSElement
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Получает или задает фактический текст для элемента структуры. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | Получает или задает выравнивание таблицы. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Получает или задает альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | Получает объектStructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | Получает или задает цвет фона таблицы. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | Получает или устанавливает границу таблицы. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | Получает или устанавливает неработающую вертикаль таблицы; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Получает дочернюю коллекцию объектовElement. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | Получает или задает настройку столбца таблицы. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | Получает ширину столбцов таблицы. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | Получает или задает стили углов границы |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | Получает объектAttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | Получает границу ячейки по умолчанию. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | Получает или задает заполнение ячейки по умолчанию. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | Получает или задает состояние текста ячейки по умолчанию. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | Получает или задает ширину столбца по умолчанию. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Получает или задает текст расширения для элемента структуры. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Получает идентификатор элемента структуры. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | Получает или устанавливает границу, включенную в ширину столбца. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | Получает или устанавливает, что таблица сломана - будет усечена для следующей страницы. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Получает или задает язык для элемента структуры. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | Получает или задает левую координату стола. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Получить родительский элемент. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | Получает или задает максимальное количество столбцов для таблицы. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | Получает количество первых строк, повторяющихся для нескольких страниц. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | Получает стиль для повторяющихся строк. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Получает или устанавливает заголовок элемента структуры. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | Получает или задает координату верхней части стола. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | ДобавитьElementк коллекции дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Изменить родительский элемент для текущего элемента структуры |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Очистить идентификатор элемента структуры. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | Создает[`TableTHeadElement`](../tabletheadelement)и добавляет его в текущую таблицу. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | Создает[`TableTFootElement`](../tabletfootelement)и добавляет его в текущую таблицу. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | Создает[`TableTHeadElement`](../tabletheadelement)и добавляет его в текущую таблицу. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Найти элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Генерировать ID для элемента структуры. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Устанавливает идентификатор элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Устанавливает пользовательский тег для элемента структуры. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Возвращает строку, представляющую текущий объект. |

### Смотрите также

* class [BLSElement](../blselement)
* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
