---
title: "Aspose::Pdf::Vector::GraphicElementCollection класс"
linktitle: "GraphicElementCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Vector::GraphicElementCollection класс. Представляет коллекцию GraphicElement в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.vector/graphicelementcollection/
---
## GraphicElementCollection class


Представляет коллекцию [GraphicElement](../graphicelement/).

```cpp
class GraphicElementCollection : public System::Collections::Generic::ICollection<System::SharedPtr<GraphicElement>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<GraphicElement\>\&) override | Добавляет новый [GraphicElement](../graphicelement/) в коллекцию. Все элементы в коллекции должны иметь одинаковый [GraphicElement::Parent](../). |
| [Clear](./clear/)() override | Очищает коллекцию. |
| [Contains](./contains/)(const System::SharedPtr\<GraphicElement\>\&) const override | Определяет, находится ли элемент в коллекции. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<GraphicElement\>\>, int32_t) override | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [get_Count](./get_count/)() const override | Получает количество объектов [GraphicElement](../graphicelement/), фактически содержащихся в коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для всей коллекции. |
| [GraphicElementCollection](./graphicelementcollection/)() | Инициализирует новую коллекцию. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент [GraphicElement](../graphicelement/) по указанному индексу. |
| [Remove](./remove/)(const System::SharedPtr\<GraphicElement\>\&) override | Удаляет элемент [GraphicElement](../graphicelement/). |
| [ToString](./tostring/)() const override | Получает строковое представление этой коллекции. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
