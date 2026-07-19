---
title: "Aspose::Pdf::Annotations::ActionCollection класс"
linktitle: "ActionCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::ActionCollection класс. Коллекция действий в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/actioncollection/
---
## ActionCollection class


[Collection](../../aspose.pdf/collection/) of actions.

```cpp
class ActionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<PdfAction>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<PdfAction\>\&) override | Добавляет новое действие в коллекцию. |
| [Clear](./clear/)() override | Очищает коллекцию. |
| [Contains](./contains/)(const System::SharedPtr\<PdfAction\>\&) const override | Возвращает true, если указанный элемент присутствует в коллекции. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<PdfAction\>\>, int32_t) override | Копирует массив действий в коллекцию. |
| [Delete](./delete/)(int32_t) | Удаляет действие из коллекции по индексу. |
| [Delete](./delete/)() | Удаляет все действия. |
| [get_Count](./get_count/)() const override | Количество действий в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Возвращает true, если коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если объект синхронизирован. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект синхронизации. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает действие по его индексу. |
| [Remove](./remove/)(const System::SharedPtr\<PdfAction\>\&) override | Удаляет элемент из коллекции. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
