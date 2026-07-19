---
title: "Aspose::Pdf::Text::TextSegmentCollection класс"
linktitle: "TextSegmentCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextSegmentCollection класс. Представляет коллекцию текстовых сегментов в C++."
type: docs
weight: 5200
url: /ru/cpp/aspose.pdf.text/textsegmentcollection/
---
## TextSegmentCollection class


Представляет коллекцию сегментов текста.

```cpp
class TextSegmentCollection : public System::Collections::Generic::ICollection<System::SharedPtr<TextSegment>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<TextSegment\>\&) override | Добавляет элемент текстового сегмента в указанном индексе. |
| [Clear](./clear/)() override | Очищает все элементы из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<TextSegment\>\&) const override | Определяет, содержит ли коллекция определённое значение. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<TextSegment\>\>, int32_t) override | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [get_Count](./get_count/)() const override | Получает количество элементов объектов [TextSegment](../textsegment/), фактически содержащихся в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект, который может использоваться для синхронизации доступа к коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для всей коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент текстового сегмента в указанном индексе. |
| [Remove](./remove/)(const System::SharedPtr\<TextSegment\>\&) override | Удаляет указанный элемент из коллекции. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
