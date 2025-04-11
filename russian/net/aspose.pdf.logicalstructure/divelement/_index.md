---
title: Class DivElement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.DivElement. Представляет элемент структуры Div в логической структуре
type: docs
weight: 6300
url: /ru/net/aspose.pdf.logicalstructure/divelement/
---
## Класс DivElement

Представляет элемент структуры Div в логической структуре.

```csharp
public sealed class DivElement : GroupingElement
```

## Свойства

| Name | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Получает или задаёт фактический текст для элемента структуры. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Получает или задаёт альтернативный текст для элемента структуры. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Получает объект StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Получает объект AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Получает или задаёт текст расширения для элемента структуры. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Получает идентификатор для элемента структуры. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Получает или задаёт язык для элемента структуры. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Получает страницу, на которой будут отображаться некоторые или все дочерние элементы. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получает родительский элемент. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Получает тип элемента структуры. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Получает или задаёт заголовок для элемента структуры. |

## Методы

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавляет Element в коллекцию дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Изменяет родительский элемент для текущего элемента структуры. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очищает все дочерние элементы. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Очищает идентификатор для элемента структуры. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Находит элементы заданного типа. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Генерирует идентификатор для элемента структуры. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставляет Element в коллекцию дочерних элементов по указанному индексу. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Удаляет: элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Удаляет элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. Вставляет дочерние объекты удалённого объекта в коллекцию дочерних элементов его бывшего родителя, начиная с индекса удалённого объекта. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удаляет дочерний элемент по индексу. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Устанавливает идентификатор для элемента структуры. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Устанавливает пользовательский тег для элемента структуры. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Связывает элемент структуры с Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Связывает элемент структуры с Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Связывает элемент структуры с оператором BDC в потоке контента. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Связывает элемент структуры с XForm в потоке контента. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Связывает элемент структуры с XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* класс [GroupingElement](../groupingelement/)
* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* сборка [Aspose.PDF](../../)