---
title: "Класс Aspose::Pdf::XFormCollection"
linktitle: "XFormCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::XFormCollection. Класс представляет коллекцию XFormCollection в C++."
type: docs
weight: 19600
url: /ru/cpp/aspose.pdf/xformcollection/
---
## XFormCollection class


Класс представляет коллекцию [XFormCollection](./).

```cpp
class XFormCollection : public System::Collections::Generic::ICollection<System::SharedPtr<XForm>>,
                        public Aspose::Pdf::ISupportsMemoryCleanup
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XForm\>\&) override | Добавляет новый [XForm](../xform/) в коллекцию. |
| [Clear](./clear/)() override | Очищает все элементы из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<XForm\>\&) const override | Определяет, содержит ли коллекция определённое значение. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<XForm\>\>, int32_t) override | Копирует [XFormCollection](./) в коллекцию. |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(const System::SharedPtr\<XForm\>\&) |  |
| [Delete](./delete/)(int32_t) | Удаляет [XForm](../xform/) из коллекции. |
| [Delete](./delete/)() | Удаляет все XForms из коллекции. |
| [Delete](./delete/)(const System::String\&) | Удаляет [XForm](../xform/) из коллекции по имени формы. |
| [FreeMemory](./freememory/)() override | Очищает кэшированные данные, освобождает память и т.д. |
| [get_Count](./get_count/)() const override | Получает количество XForms в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если объект синхронизирован. |
| [get_SyncRoot](./get_syncroot/)() const | Объект синхронизации. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель коллекции. |
| [GetFormName](./getformname/)(const System::SharedPtr\<XForm\>\&) | Возвращает имя формы в этой коллекции форм. |
| [idx_get](./idx_get/)(int32_t) | Возвращает [XForm](../xform/) по индексу. |
| [idx_get](./idx_get/)(const System::String\&) | Возвращает [XForm](../xform/) по его имени. Исключение выбрасывается, если [XForm](../xform/) с указанным именем не найден. |
| [Remove](./remove/)(const System::SharedPtr\<XForm\>\&) override | Удаляет указанный элемент из коллекции. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
