---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.LogicalStructure.Element. Представляет базовый класс для элемента в логической структуре
type: docs
weight: 6320
url: /ru/net/aspose.pdf.logicalstructure/element/
---
## Класс Element

Представляет базовый класс для элемента в логической структуре.

```csharp
public abstract class Element
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получает родительский элемент. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавляет элемент в коллекцию дочерних. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очищает всех детей. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Находит элементы заданного типа |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставляет элемент в коллекцию дочерних по указанному индексу. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удаляет ребенка по индексу. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Привязывает элемент структуры к аннотации. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Привязывает элемент структуры к артефакту. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Привязывает элемент структуры к оператору BDC потока содержимого. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Привязывает элемент структуры к XForm потока содержимого. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Привязывает элемент структуры к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* пространство имен [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* сборка [Aspose.PDF](../../)