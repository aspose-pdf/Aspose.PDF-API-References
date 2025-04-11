---
title: Class StructTreeRootElement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.StructTreeRootElement. Представляет объект StructTreeRoot в логической структуре
type: docs
weight: 6660
url: /ru/net/aspose.pdf.logicalstructure/structtreerootelement/
---
## StructTreeRootElement class

Представляет объект StructTreeRoot в логической структуре.

```csharp
public sealed class StructTreeRootElement : Element
```

## Properties

| Name | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получает родительский элемент. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавляет элемент в коллекцию дочерних. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очищает всех детей. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Находит элементы заданного типа |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставляет элемент в коллекцию дочерних по указанному индексу. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удаляет ребенка по индексу. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_2)(Annotation) | Привязывает элемент структуры к аннотации. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag)(Artifact) | Привязывает элемент структуры к артефакту. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_1)(BDC) | Привязывает элемент структуры к оператору BDC потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_3)(XForm) | Привязывает элемент структуры к XForm потока содержимого. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_4)(XImage) | Привязывает элемент структуры к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Возвращает строку, представляющую текущий объект. |

### See Also

* class [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)