---
title: "Aspose::Pdf::Forms::OptionCollection класс"
linktitle: "OptionCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::OptionCollection класс. Класс, представляющий коллекцию вариантов поля выбора в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf.forms/optioncollection/
---
## OptionCollection class


Класс, представляющий коллекцию вариантов поля выбора.

```cpp
class OptionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Option>>
```

## Методы

| Метод | Описание |
| --- | --- |
|  | [Add](./add/)(const System::SharedPtr\<Option\>\&) override | Добавляет элемент в коллекцию, бросает NotImplementedException |
. |
| [Clear](./clear/)() override | Удаляет все элементы из коллекции. |
|  | [Contains](./contains/)(const System::SharedPtr\<Option\>\&) const override | Проверяет, существует ли элемент в коллекции, бросает NotImplementedException |
. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Option\>\>, int32_t) override | Копирует варианты в массив. |
| [get](./get/)(int32_t) | Получает вариант по индексу. |
| [get](./get/)(const System::String\&) | Получает вариант из коллекции по имени варианта. |
| [get_Count](./get_count/)() const override | Получает количество вариантов. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если объект синхронизирован. |
| [get_SyncRoot](./get_syncroot/)() const | Объект синхронизации коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для вариантов в коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает вариант по индексу. |
| [idx_get](./idx_get/)(const System::String\&) | Получает вариант по его имени. |
|  | [Remove](./remove/)(const System::SharedPtr\<Option\>\&) override | Удаляет элемент из коллекции, бросает NotImplementedException |
. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
