---
title: "Класс System::Collections::Generic::LinkedListNode"
linktitle: "LinkedListNode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::LinkedListNode. Узел связного списка. Реализует обёртку над итератором std::list, который обернут в связный список. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3200
url: /ru/cpp/system.collections.generic/linkedlistnode/
---
## LinkedListNode class


Узел связного списка. Реализует обёртку над итератором std::list, который обернут в связный список. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T>class LinkedListNode : public System::Object
```


| Параметр | Описание |
| --- | --- |
| T | Тип хранимого значения. |
## Методы

| Метод | Описание |
| --- | --- |
| [get_List](./get_list/)() const | Получает содержащий список. |
| [get_Next](./get_next/)() const | Получает следующий узел. |
| [get_Previous](./get_previous/)() const | Получает предыдущий узел. |
| [get_Value](./get_value/)() const | Получает хранимое значение. |
| [LinkedListNode](./linkedlistnode/)(const T\&) | Конструктор. |
| [set_Value](./set_value/)(const T\&) | Устанавливает хранимое значение. |

## См. также

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
