---
title: "класс Aspose::Pdf::LogicalStructure::Element"
linktitle: "Элемент"
second_title: "Справочник API Aspose.PDF для C++"
description: "класс Aspose::Pdf::LogicalStructure::Element. Представляет базовый класс для элементов в логической структуре на C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.logicalstructure/element/
---
## Element class


Представляет базовый класс для элемента в логической структуре.

```cpp
class Element : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [AppendChild](./appendchild/)(const System::SharedPtr\<Element\>\&, bool) | Добавить [T:/Aspose::Pdf::LogicalStructure::Element](../) в коллекцию дочерних элементов. |
| [ClearChilds](./clearchilds/)() | Очистить всех дочерних элементов. |
| [FindElements](./findelements/)(bool) | Найти элементы заданного типа. |
| [get_ChildElements](./get_childelements/)() | Получает коллекцию дочерних объектов [T:/Aspose::Pdf::LogicalStructure::Element](../). |
| [get_ParentElement](./get_parentelement/)() const | Получить родительский элемент. |
| [InsertChild](./insertchild/)(const System::SharedPtr\<Element\>\&, int32_t, bool) | Вставить [T:/Aspose::Pdf::LogicalStructure::Element](../) в коллекцию дочерних элементов по указанному индексу. |
| [RemoveChild](./removechild/)(int32_t) | Удалить дочерний элемент по индексу. |
| virtual [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) | Привязать элемент структуры к оператору BDC потока содержимого. |
| virtual [Tag](./tag/)(System::SharedPtr\<XForm\>) | Привязать элемент структуры к потоку содержимого [XForm](../../aspose.pdf/xform/). |
| virtual [Tag](./tag/)(System::SharedPtr\<XImage\>) | Привязать элемент структуры к [XImage](../../aspose.pdf/ximage/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Artifact\>) | Привязать элемент структуры к [Artifact](../../aspose.pdf/artifact/). |
| virtual [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) | Привязать элемент структуры к аннотации. |
| [ToString](./tostring/)() const override | Возвращает строку, представляющую текущий объект. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
