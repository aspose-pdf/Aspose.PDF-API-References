---
title: Class TableTHeadElement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.TableTHeadElement. Представляет элемент структуры THead в логической структуре таблицы
type: docs
weight: 6840
url: /ru/net/aspose.pdf.logicalstructure/tabletheadelement/
---
## Класс TableTHeadElement

Представляет элемент структуры THead в логической структуре таблицы.

```csharp
public sealed class TableTHeadElement : TableRowCollectionElement
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Получает или задает фактический текст для элемента структуры. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Получает или задает альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Получает объект StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Получает объект AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Получает или задает текст расширения для элемента структуры. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Получает ID для элемента структуры. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Получает или задает язык для элемента структуры. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Получает страницу, на которой будут отображены некоторые или все дочерние элементы. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получает родительский элемент. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Получает или задает заголовок для элемента структуры. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавляет элемент в коллекцию дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Изменяет родительский элемент для текущего элемента структуры |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очищает всех детей. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Очищает ID для элемента структуры. |
| virtual [CreateTR](../../aspose.pdf.logicalstructure/tablerowcollectionelement/createtr/)() | Создает [`TableTRElement`](../tabletrelement/) и добавляет его в текущую таблицу. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Находит элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Генерирует ID для элемента структуры. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставляет элемент в коллекцию дочерних элементов по указанному индексу. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Удаляет: элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов, соответствующий объект из документа. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Удаляет элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. Вставляет дочерние объекты удаленного объекта в коллекцию дочерних объектов его бывшего родителя, начиная с индекса удаленного объекта. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удаляет ребенка по индексу. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Устанавливает ID для элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Устанавливает пользовательский тег для элемента структуры. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Привязывает элемент структуры к аннотации. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Привязывает элемент структуры к артефакту. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Привязывает элемент структуры к оператору BDC потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Привязывает элемент структуры к XForm потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Привязывает элемент структуры к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* класс [TableRowCollectionElement](../tablerowcollectionelement/)
* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* сборка [Aspose.PDF](../../)