---
title: "Класс Aspose::Pdf::Text::FontCollection"
linktitle: "FontCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Text::FontCollection. Представляет коллекцию шрифтов в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf.text/fontcollection/
---
## FontCollection class


Представляет коллекцию шрифтов.

```cpp
class FontCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Font>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Font\>\&, System::String\&) | Добавляет новый шрифт в ресурсы шрифтов и возвращает автоматически присвоенное имя ресурса шрифта. |
| [Contains](./contains/)(const System::String\&) const | Проверяет, существует ли шрифт в коллекции шрифтов. |
| [Contains](./contains/)(const System::SharedPtr\<Font\>\&) const override | Определяет, содержит ли коллекция определённое значение. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Font\>\>, int32_t) override | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [get_Count](./get_count/)() const override | Получает количество элементов объектов [Font](../font/), фактически содержащихся в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Возвращает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект, который может использоваться для синхронизации доступа к коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для всей коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент шрифта по указанному индексу. |
| [idx_get](./idx_get/)(const System::String\&) | Получает шрифт из коллекции по имени шрифта. Исключение выбрасывается, если шрифт не найден. |
| [Remove](./remove/)(const System::SharedPtr\<Font\>\&) override | Удаляет указанный элемент из коллекции. |
## Примечания


[Font](../font/) collections represented by [FontCollection](./) class are used in several scenarios. For example, in resources with [Resources::Fonts](../) property. 
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
