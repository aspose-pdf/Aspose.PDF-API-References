---
title: Class StructureElement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.StructureElement. Представляет базовый класс для структурных элементов в логической структуре
type: docs
weight: 6700
url: /ru/net/aspose.pdf.logicalstructure/structureelement/
---
## Класс StructureElement

Представляет базовый класс для структурных элементов в логической структуре.

```csharp
public abstract class StructureElement : Element
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Получает или задает фактический текст для структурного элемента. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Получает или задает альтернативный текст для структурного элемента. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Получает объект StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Получает объект AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Получает или задает текст расширения для структурного элемента. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Получает ID для структурного элемента. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Получает или задает язык для структурного элемента. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Получает страницу, на которой будут отображены некоторые или все дочерние элементы. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получает родительский элемент. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Получает тип структурного элемента. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Получает или задает заголовок для структурного элемента. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавляет элемент в коллекцию дочерних элементов. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Изменяет родительский элемент для текущего структурного элемента |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очищает всех детей. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Очищает ID для структурного элемента. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Находит элементы заданного типа |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Генерирует ID для структурного элемента. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставляет элемент в коллекцию дочерних элементов по указанному индексу. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Удаляет: элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов, соответствующий объект из документа. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Удаляет элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. Вставляет дочерние объекты удаленного объекта в коллекцию дочерних объектов его прежнего родителя, начиная с индекса удаленного объекта. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удаляет дочерний элемент по индексу. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Устанавливает ID для структурного элемента. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Устанавливает пользовательский тег для структурного элемента. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_2)(Annotation) | Привязывает структурный элемент к аннотации. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag)(Artifact) | Привязывает структурный элемент к артефакту. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_1)(BDC) | Привязывает структурный элемент к оператору BDC потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_3)(XForm) | Привязывает структурный элемент к XForm потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_4)(XImage) | Привязывает структурный элемент к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* класс [Element](../element/)
* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* сборка [Aspose.PDF](../../)