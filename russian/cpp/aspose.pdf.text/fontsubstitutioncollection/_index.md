---
title: "Aspose::Pdf::Text::FontSubstitutionCollection класс"
linktitle: "FontSubstitutionCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::FontSubstitutionCollection класс. Представляет коллекцию стратегий замены шрифтов в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf.text/fontsubstitutioncollection/
---
## FontSubstitutionCollection class


Представляет коллекцию стратегий замены шрифтов.

```cpp
class FontSubstitutionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FontSubstitution>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FontSubstitution\>\&) override | Добавляет новый объект замены шрифта в коллекцию. |
| [Clear](./clear/)() override | Очищает коллекцию замен шрифтов. |
| [Contains](./contains/)(const System::SharedPtr\<FontSubstitution\>\&) const override | Определяет, находится ли элемент в коллекции. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FontSubstitution\>\>, int32_t) override | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [get_Count](./get_count/)() const override | Получает количество элементов объектов [Font](../font/), фактически содержащихся в коллекции. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект, который может использоваться для синхронизации доступа к коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для всей коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент шрифта по указанному индексу. |
| [Remove](./remove/)(const System::SharedPtr\<FontSubstitution\>\&) override | Удаляет элемент замены шрифта. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
