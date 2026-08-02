---
title: "Класс Element"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.LogicalStructure.Element класс. Представляет базовый класс для элемента в логической структуре"
type: docs
weight: 6460
url: /ru/net/aspose.pdf.logicalstructure/element/
---
## Element class

Представляет базовый класс для элемента в логической структуре.

```csharp
public abstract class Element
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Получает коллекцию дочерних объектов Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Получить родительский элемент. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Добавить Element в коллекцию дочерних элементов. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Очистить все дочерние элементы. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Найти элементы заданного типа |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Вставить Element в коллекцию дочерних элементов по указанному индексу. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Удалить дочерний элемент в позиции. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Привязывает элемент структуры к Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Привязывает элемент структуры к Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Привязывает элемент структуры к оператору BDC в потоке содержимого. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Привязывает элемент структуры к XForm в потоке содержимого. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Привязывает элемент структуры к XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Возвращает строку, представляющую текущий объект. |

### См. также

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


