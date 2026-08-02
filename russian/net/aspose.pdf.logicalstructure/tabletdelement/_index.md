---
title: "Класс TableTDElement"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.LogicalStructure.TableTDElement класс. Представляет элемент структуры TD в логической структуре таблицы"
type: docs
weight: 6950
url: /ru/net/aspose.pdf.logicalstructure/tabletdelement/
---
## TableTDElement class

Представляет элемент структуры TD в логической структуре таблицы.

```csharp
public sealed class TableTDElement : TableCellElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Получает или задает фактический текст для элемента структуры. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Получает или задаёт выравнивание ячейки. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Получает или задает альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Получает объект StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Получает или задаёт цвет фона ячейки. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Получает или задаёт границу ячейки. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Получает или задаёт охват колонок. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Получает объект AttributeOwnerStandard. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Получает или задаёт состояние текста ячейки по умолчанию. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Получает или задает расширяющий текст для элемента структуры. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Получает ID элемента структуры. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Получает или задаёт наличие границы у ячейки. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Получает или задает перенос слов текста ячейки. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Получает или задает язык для элемента структуры. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Получает или задаёт отступ. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Получает страницу, на которой будут отрисованы некоторые или все дочерние элементы. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получить родительский элемент. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Получает или задает объединение строк. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Получает объект StructureTextState для текущего элемента. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Получает или задает заголовок для элемента структуры. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание. |

## Методы

| Имя | Описание |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавить Element в коллекцию дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Изменить родительский элемент для текущего элемента структуры |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очистить все дочерние элементы. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Очистить ID элемента структуры. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Найти элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Сгенерировать ID для элемента структуры. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставить Element в коллекцию дочерних элементов по указанному индексу. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Удаляет: элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов, соответствующий объект из документа. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Удаляет элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. Вставляет дочерние объекты удалённого объекта в прежнюю коллекцию дочерних объектов родителя, начиная с индекса удалённого объекта. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удалить дочерний элемент в позиции. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Устанавливает ID для элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Устанавливает пользовательский тег для элемента структуры. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Привязывает элемент структуры к Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Привязывает элемент структуры к Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Привязывает элемент структуры к оператору BDC в потоке содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Привязывает элемент структуры к XForm в потоке содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Привязывает элемент структуры к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* class [TableCellElement](../tablecellelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


