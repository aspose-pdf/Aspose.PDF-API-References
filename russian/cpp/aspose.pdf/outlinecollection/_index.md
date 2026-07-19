---
title: "Класс Aspose::Pdf::OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::OutlineCollection. Представляет иерархию оглавления документа в C++."
type: docs
weight: 12500
url: /ru/cpp/aspose.pdf/outlinecollection/
---
## OutlineCollection class


Представляет иерархию оглавления документа.

```cpp
class OutlineCollection : public Aspose::Pdf::Outlines
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Добавляет элемент оглавления в коллекцию. |
| [Clear](./clear/)() override | Очищает все элементы из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Проверяет, содержит ли коллекция указанный элемент. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Копирует элементы оглавления в [System.Array](../../system/array/), начиная с указанного индекса [System.Array](../../system/array/). |
| [Delete](./delete/)() | Удаляет все элементы оглавления из оглавления документа. |
| [Delete](./delete/)(const System::String\&) | Удаляет элемент оглавления с указанным заголовком из оглавления документа. |
| [get_Count](./get_count/)() const override | Количество элементов в коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount возвращает число видимых элементов оглавления на всех уровнях. |
| [get_First](./get_first/)() const | Получает элемент оглавления, представляющий первый элемент верхнего уровня в оглавлении. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (потокобезопасный). |
| [get_Last](./get_last/)() | Получает элемент оглавления, представляющий последний элемент верхнего уровня в оглавлении. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [get_VisibleCount](./get_visiblecount/)() override | Count — это сумма количества видимых дочерних элементов оглавления на всех уровнях. [Note](../note/): пожалуйста, не путайте с Count, который является числом элементов в коллекции. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель, который проходит по коллекции. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент оглавления из коллекции по индексу. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Всегда бросает NotImplementedException |
| [Remove](./remove/)(int32_t) | Удалить элемент по индексу. |
## См. также

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
