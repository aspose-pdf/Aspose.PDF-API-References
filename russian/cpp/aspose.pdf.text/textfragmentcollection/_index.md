---
title: "Aspose::Pdf::Text::TextFragmentCollection class"
linktitle: "TextFragmentCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextFragmentCollection class. Представляет коллекцию текстовых фрагментов в C++."
type: docs
weight: 4500
url: /ru/cpp/aspose.pdf.text/textfragmentcollection/
---
## TextFragmentCollection class


Представляет коллекцию фрагментов текста.

```cpp
class TextFragmentCollection : public System::Collections::Generic::ICollection<System::SharedPtr<TextFragment>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<TextFragment\>\&) override | Добавляет элемент текстового фрагмента по указанному индексу. |
| [Clear](./clear/)() override | Очищает все элементы из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<TextFragment\>\&) const override | Определяет, содержит ли коллекция определённое значение. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<TextFragment\>\>, int32_t) override | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [get_Count](./get_count/)() const override | Получает количество элементов объектов [TextFragment](../textfragment/), фактически содержащихся в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект, который может использоваться для синхронизации доступа к коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для всей коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент текстового фрагмента по указанному индексу. |
| [Remove](./remove/)(const System::SharedPtr\<TextFragment\>\&) override | Удаляет указанный элемент из коллекции и также удаляет его из документа. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
