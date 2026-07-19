---
title: "System::Collections::Generic::StackPtr класс"
linktitle: "StackPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::StackPtr класс. Указатель стека. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции либо по значению, либо по константной ссылке в C++."
type: docs
weight: 4700
url: /ru/cpp/system.collections.generic/stackptr/
---
## StackPtr class


[Stack](../stack/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<T0>
```


| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [StackPtr](./stackptr/)() | Создаёт нулевой указатель. |
| [StackPtr](./stackptr/)(const SharedPtr\<Stack\<T\>\>\&) | Создаёт указатель, ссылающийся на конкретный стек. |

## См. также

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
