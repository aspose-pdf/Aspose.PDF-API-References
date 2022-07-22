---
title: TableCellElement
second_title: Aspose.PDF для справочника API .NET
description: Представляет базовый класс для элементов ячеек таблицы TH и TD в логической структуре.
type: docs
weight: 4590
url: /ru/net/aspose.pdf.logicalstructure/tablecellelement/
---
## TableCellElement class

Представляет базовый класс для элементов ячеек таблицы (TH и TD) в логической структуре.

```csharp
public abstract class TableCellElement : TableChildElement, ITextElement
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Получает или задает фактический текст для элемента структуры. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment) { get; set; } | Получает или задает выравнивание ячеек. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Получает или задает альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | получаетStructureAttributeCollection объект. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor) { get; set; } | Получает или задает цвет фона ячейки. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border) { get; set; } | Получает или задает границу ячейки. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Получает дочернюю коллекциюElement объекты. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan) { get; set; } | Получает или задает диапазон столбца. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | получаетAttributeOwnerStandard объект. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate) { get; set; } | Получает или задает состояние текста ячейки по умолчанию. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Получает или задает текст расширения для элемента структуры. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Получает идентификатор элемента структуры. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder) { get; set; } | Получает или устанавливает границу ячейки. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped) { get; set; } | Получает или задает текстовое слово ячейки, обернутое. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Получает или задает язык для элемента структуры. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin) { get; set; } | Получает или задает заполнение. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Получить родительский элемент. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan) { get; set; } | Получает или задает диапазон строк. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate) { get; } | получаетStructureTextState объект для текущего элемента. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Получает или задает заголовок элемента структуры. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | ДобавитьElement в коллекцию детей. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Изменить родительский элемент для текущей структуры element |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Очистить идентификатор элемента структуры. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Найти элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Создать идентификатор для элемента структуры. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Устанавливает ID для элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Устанавливает пользовательский тег для элемента структуры. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext)(string) | Добавляет текстовое содержимое к текущему текстовому элементу. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Возвращает строку, представляющую текущий объект. |

### Смотрите также

* class [TableChildElement](../tablechildelement)
* interface [ITextElement](../itextelement)
* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
