---
title: TableTRElement
second_title: Aspose.PDF для справочника API .NET
description: Представляет элемент структуры TR в логической структуре таблицы.
type: docs
weight: 4680
url: /ru/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class

Представляет элемент структуры TR в логической структуре таблицы.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Получает или задает фактический текст для элемента структуры. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Получает или задает альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | Получает объектStructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor) { get; set; } | Получает или задает цвет фона строки. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border) { get; set; } | Получает или задает границу строки. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Получает дочернюю коллекцию объектовElement. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | Получает объектAttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder) { get; set; } | Получает границу ячейки по умолчанию. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding) { get; set; } | Получает или задает поле по умолчанию для ячеек строки. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate) { get; set; } | Получает или задает состояние текста по умолчанию для ячеек строк |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Получает или задает текст расширения для элемента структуры. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight) { get; set; } | Получает фиксированную высоту строки - строка может иметь фиксированную высоту. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Получает идентификатор элемента структуры. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage) { get; set; } | Получает фиксированную строку на новой странице - страница с этим свойством должна быть напечатана на следующей странице По умолчанию false. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken) { get; set; } | Получает строку, которая может быть разбита между двумя страницами. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Получает или задает язык для элемента структуры. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight) { get; set; } | Получает высоту строки. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Получить родительский элемент. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Получает или устанавливает заголовок элемента структуры. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | ДобавитьElementк коллекции дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Изменить родительский элемент для текущего элемента структуры |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Очистить идентификатор элемента структуры. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd)() | Создает[`TableTHElement`](../tablethelement)и добавляет его в текущую таблицу. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth)() | Создает[`TableTHElement`](../tablethelement)и добавляет его в текущую таблицу. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Найти элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Генерировать ID для элемента структуры. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Устанавливает идентификатор элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Устанавливает пользовательский тег для элемента структуры. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Возвращает строку, представляющую текущий объект. |

### Смотрите также

* class [TableChildElement](../tablechildelement)
* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
