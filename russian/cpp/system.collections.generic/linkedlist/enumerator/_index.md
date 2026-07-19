---
title: "System::Collections::Generic::LinkedList::Enumerator класс"
linktitle: "Перечислитель"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::LinkedList::Enumerator класс. Перечислитель для обхода связного списка в C++."
type: docs
weight: 3600
url: /ru/cpp/system.collections.generic/linkedlist/enumerator/
---
## Enumerator class


[Enumerator](./) to iterate through linked list.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<T>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<LinkedList\<T\>\>\&) | Создаёт перечислитель. |
| [get_Current](./get_current/)() const override | Получает текущий элемент. |
| [MoveNext](./movenext/)() override | Перемещает перечислитель к следующему элементу (если есть). |
## См. также

* Class [Object](../../../system/object/)
* Class [IEnumerator](../../ienumerator/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
