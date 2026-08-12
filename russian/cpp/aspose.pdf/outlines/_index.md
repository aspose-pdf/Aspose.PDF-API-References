---
title: "Класс Aspose::Pdf::Outlines"
linktitle: "Outlines"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Outlines. Класс описывает коллекцию оглавлений в C++."
type: docs
weight: 12700
url: /ru/cpp/aspose.pdf/outlines/
---
## Outlines class


Класс описывает коллекцию оглавлений.

```cpp
class Outlines : public System::Collections::Generic::ICollection<System::SharedPtr<OutlineItemCollection>>
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Добавляет элемент оглавления в коллекцию. |
| virtual [Clear](./clear/)() | Очищает все элементы из коллекции. |
| virtual [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const | Всегда бросает NotImplementedException. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) | Копирует элементы оглавления в [System.Array](../../system/array/), начиная с определённого индекса [System.Array](../../system/array/). |
| virtual [get_Count](./get_count/)() const | Получает количество. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Получает значение, указывающее, является ли коллекция только для чтения. |
| virtual [get_VisibleCount](./get_visiblecount/)() | Получает общее количество элементов оглавления на всех уровнях в иерархии оглавления документа. |
| virtual [GetEnumerator](./getenumerator/)() | Возвращает перечислитель, который проходит по коллекции. |
| virtual [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Удаляет элемент коллекции оглавления. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
