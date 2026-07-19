---
title: "Класс Aspose::Pdf::PageCollection"
linktitle: "PageCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::PageCollection. Коллекция страниц PDF‑документа в C++."
type: docs
weight: 13200
url: /ru/cpp/aspose.pdf/pagecollection/
---
## PageCollection class


[Collection](../collection/) of PDF document pages.

```cpp
class PageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Page>>,
                       public Aspose::Pdf::ISupportsMemoryCleanup
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<Annotations::AnnotationSelector\>\&) | Принимает объект‑посетитель [AnnotationSelector](../), который предоставляет возможности работы с аннотациями. |
| [Accept](./accept/)(const System::SharedPtr\<ImagePlacementAbsorber\>\&) | Принимает объект‑посетитель [ImagePlacementAbsorber](../imageplacementabsorber/), который предоставляет возможности работы с объектами размещения изображений. |
| [Accept](./accept/)(const System::SharedPtr\<Text::TextFragmentAbsorber\>\&) | Принимает объект‑посетитель [TextFragmentAbsorber](../), который предоставляет возможности работы с текстовыми объектами. |
| [Accept](./accept/)(const System::SharedPtr\<Text::TextAbsorber\>\&) | Принимает объект‑посетитель [TextAbsorber](../), который предоставляет возможности работы с текстовыми объектами. |
| [Add](./add/)() | Добавляет пустую страницу. Если документ уже содержит страницы разного размера, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) | Добавляет в коллекцию все страницы из списка. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) | Добавляет в коллекцию все страницы из массива. |
| [BeginUpdate](./beginupdate/)() | Обновления происходят, когда начинаются изменения группы. Останавливает пересчёт кэша страниц при каждой операции. Мы рекомендуем вызывать методы BeginUpdate/EndUpdate в блоке try‑finally. |
| [Clear](./clear/)() override | Очистить коллекцию страниц. |
| [Contains](./contains/)(const System::SharedPtr\<Page\>\&) const override | Определяет, содержит ли данный экземпляр объект. |
| [CopyPage](./copypage/)(const System::SharedPtr\<Page\>\&) | Добавляет страницу в коллекцию. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Page\>\>, int32_t) override | Копирует страницы в документ. |
| [Delete](./delete/)(int32_t) | Удалить указанную страницу. |
| [Delete](./delete/)() | Удаляет все страницы из коллекции. |
| [Delete](./delete/)(const System::ArrayPtr\<int32_t\>\&) | Удалить страницы, номера которых указаны в массиве. |
| [EndUpdate](./endupdate/)() | Обновляет данные после завершения групповых изменений. Восстанавливает пересчёт кэша страниц при каждой операции. Мы рекомендуем вызывать методы BeginUpdate/EndUpdate в блоке try-finally. |
| [Flatten](./flatten/)() | Удаляет все поля, расположенные на страницах, и вместо них размещает их значения. |
| [FreeMemory](./freememory/)() override | Очищает кэшированные данные. |
| [get_Count](./get_count/)() const override | Получает количество страниц в документе. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, что коллекция только для чтения. Всегда возвращает false. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если объект синхронизирован. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект синхронизации коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель страниц. |
| [idx_get](./idx_get/)(int32_t) | Получает страницу по индексу. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Page\>\&) const | Возвращает индекс указанной страницы. |
| [Insert](./insert/)(int32_t) | Вставляет пустую страницу в коллекцию в указанную позицию. Если документ уже содержит страницы разных размеров, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<Page\>\&) | Вставляет страницу в коллекцию страниц в указанное место. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) | Вставляет страницы из коллекции в документ. |
| [Insert](./insert/)(int32_t, const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) | Вставляет страницы из массива в документ. |
|  | [Remove](./remove/)(const System::SharedPtr\<Page\>\&) override | Удаляет указанный элемент, бросает NotSupportedException. |
. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
