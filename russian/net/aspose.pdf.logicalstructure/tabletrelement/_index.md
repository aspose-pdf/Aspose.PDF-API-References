---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.TableTRElement. Представляет элемент структуры TR в логической структуре таблицы
type: docs
weight: 6850
url: /ru/net/aspose.pdf.logicalstructure/tabletrelement/
---
## Класс TableTRElement

Представляет элемент структуры TR в логической структуре таблицы.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Получает или задает фактический текст для элемента структуры. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Получает или задает альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Получает объект StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | Получает или задает цвет фона строки. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | Получает или задает границу строки. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Получает объект AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | Получает границу ячейки по умолчанию. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | Получает или задает отступ по умолчанию для ячеек строки. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | Получает или задает состояние текста по умолчанию для ячеек строки |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Получает или задает текст расширения для элемента структуры. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | Получает фиксированную высоту строки - строка может иметь фиксированную высоту. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Получает ID для элемента структуры. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | Получает, находится ли фиксированная строка на новой странице - страница с этим свойством должна быть напечатана на следующей странице. По умолчанию false. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | Получает, может ли строка быть разбита между двумя страницами. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Получает или задает язык для элемента структуры. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | Получает высоту для строки. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Получает страницу, на которой будут отображены некоторые или все дочерние элементы. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получает родительский элемент. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Получает или задает заголовок для элемента структуры. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавляет элемент в коллекцию дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Изменяет родительский элемент для текущего элемента структуры |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очищает всех детей. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Очищает ID для элемента структуры. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | Создает [`TableTHElement`](../tablethelement/) и добавляет его в текущую таблицу. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | Создает [`TableTHElement`](../tablethelement/) и добавляет его в текущую таблицу. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Находит элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Генерирует ID для элемента структуры. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставляет элемент в коллекцию дочерних элементов по указанному индексу. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Удаляет: элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов, соответствующий объект из документа. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Удаляет элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. Вставляет дочерние объекты удаленного объекта в коллекцию дочерних объектов его бывшего родителя, начиная с индекса удаленного объекта. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удаляет дочерний элемент по индексу. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Устанавливает ID для элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Устанавливает пользовательский тег для элемента структуры. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Привязывает элемент структуры к аннотации. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Привязывает элемент структуры к артефакту. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Привязывает элемент структуры к оператору BDC потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Привязывает элемент структуры к XForm потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Привязывает элемент структуры к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* класс [TableChildElement](../tablechildelement/)
* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* сборка [Aspose.PDF](../../)