---
title: "Класс Aspose::Pdf::Text::FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::FontSourceCollection class. Представляет коллекцию источников шрифтов в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.text/fontsourcecollection/
---
## FontSourceCollection class


Представляет коллекцию источников шрифтов.

```cpp
class FontSourceCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FontSource>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FontSource\>\&) override | Добавляет новый объект источника шрифта в коллекцию. |
| [Clear](./clear/)() override | Очищает коллекцию источников шрифтов. |
| [Contains](./contains/)(const System::SharedPtr\<FontSource\>\&) const override | Определяет, находится ли элемент в коллекции. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FontSource\>\>, int32_t) override | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [Delete](./delete/)(const System::SharedPtr\<FontSource\>\&) | Удаляет элемент источника шрифта. |
| [get_Count](./get_count/)() const override | Получает количество элементов объектов [Font](../font/), фактически содержащихся в коллекции. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект, который может использоваться для синхронизации доступа к коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для всей коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент шрифта по указанному индексу. |
| [Remove](./remove/)(const System::SharedPtr\<FontSource\>\&) override | Удаляет элемент источника шрифта. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
