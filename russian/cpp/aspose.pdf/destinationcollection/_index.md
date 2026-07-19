---
title: "Класс Aspose::Pdf::DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::DestinationCollection. Класс представляет коллекцию всех назначений (дерево имён, сопоставляющее строковые имена с назначениями (см. 12.3.2.3, \"Named Destinations\") и (см. 7.7.4, \"Name Dictionary\")) в PDF‑документе на C++."
type: docs
weight: 3500
url: /ru/cpp/aspose.pdf/destinationcollection/
---
## DestinationCollection class


Класс представляет коллекцию всех назначений (дерево имён, сопоставляющее строковые имена с назначениями (см. 12.3.2.3, "Named Destinations") и (см. 7.7.4, "Name Dictionary")) в PDF‑документе.

```cpp
class DestinationCollection : public System::Collections::Generic::ICollection<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Object>>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Добавляет указанный элемент. [Collection](../collection/) только для чтения. Всегда генерирует исключение NotSupportedException. |
| [Clear](./clear/)() override | [Collection](../collection/) только для чтения. Всегда генерирует исключение NotSupportedException. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) const override | Определяет, содержит ли данный экземпляр объект. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\>, int32_t) override | Копирует элементы коллекции в массив, начиная с указанного индекса массива. |
| [get_Count](./get_count/)() const override | Возвращает количество элементов, содержащихся в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель. |
| [GetExplicitDestination](./getexplicitdestination/)(const System::String\&, bool) | Возвращает явное назначение по имени. |
| [GetPageNumber](./getpagenumber/)(const System::String\&, bool) | Возвращает номер страницы назначения по имени. |
| [idx_get](./idx_get/)(int32_t) | Получает объект назначения по индексу. |
| [IndexOf](./indexof/)(System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>) const | Возвращает индекс назначения в коллекции. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Удаляет указанный элемент. [Collection](../collection/) только для чтения. Всегда генерирует исключение NotSupportedException. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
