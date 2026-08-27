---
title: "Класс TableElement"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.LogicalStructure.TableElement. Представляет элемент структуры Table в логической структуре."
type: docs
weight: 6920
url: /ru/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Представляет элемент структуры Table в логической структуре.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Получает или задает фактический текст для элемента структуры. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Получает или задает выравнивание таблицы. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Получает или задает альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Получает объект StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Получает или задает цвет фона таблицы. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Получает или задает границу таблицы. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Получает или задает вертикальное разбиение таблицы; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Получает или задает настройку столбцов таблицы. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Получает ширины столбцов таблицы. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Получает или задает стили углов границы |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Получает объект AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Получает границу ячейки по умолчанию. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Получает или задает отступ ячейки по умолчанию. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Получает или задаёт состояние текста ячейки по умолчанию. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Получает или задает ширину столбца по умолчанию. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Получает или задает расширяющий текст для элемента структуры. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Получает ID элемента структуры. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Получает или задает включение границы в ширины столбцов. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Получает или задает, что таблица разорвана — будет обрезана для следующей страницы. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Получает или задает язык для элемента структуры. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Получает или задает левую координату таблицы. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Получает страницу, на которой будут отрисованы некоторые или все дочерние элементы. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получить родительский элемент. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Получает или задает максимальное количество столбцов для таблицы. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Получает количество первых строк, повторяемых на нескольких страницах. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Получает стиль повторяющихся строк. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Получает или задает заголовок для элемента структуры. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Получает или задает верхнюю координату таблицы. |

## Методы

| Имя | Описание |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавить Element в коллекцию дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Изменить родительский элемент для текущего элемента структуры |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очистить все дочерние элементы. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Очистить ID элемента структуры. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Создаёт [`TableTHeadElement`](../tabletheadelement/) и добавляет его в текущую таблицу. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Создаёт [`TableTFootElement`](../tabletfootelement/) и добавляет его в текущую таблицу. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Создаёт [`TableTHeadElement`](../tabletheadelement/) и добавляет его в текущую таблицу. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Найти элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Сгенерировать ID для элемента структуры. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставить Element в коллекцию дочерних элементов по указанному индексу. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Удаляет: элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов, соответствующий объект из документа. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Удаляет элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. Вставляет дочерние объекты удалённого объекта в прежнюю коллекцию дочерних объектов родителя, начиная с индекса удалённого объекта. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удалить дочерний элемент в позиции. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Устанавливает ID для элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Устанавливает пользовательский тег для элемента структуры. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Привязывает элемент структуры к Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Привязывает элемент структуры к Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Привязывает элемент структуры к оператору BDC в потоке содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Привязывает элемент структуры к XForm в потоке содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Привязывает элемент структуры к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* class [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


