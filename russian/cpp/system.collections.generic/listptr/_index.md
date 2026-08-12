---
title: "System::Collections::Generic::ListPtr class"
linktitle: "ListPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::ListPtr class. Указатель списка с операторами доступа. Этот тип является указателем для управления удалением других объектов. Его следует выделять в стеке и передавать в функции либо по значению, либо по константной ссылке в C++."
type: docs
weight: 3500
url: /ru/cpp/system.collections.generic/listptr/
---
## ListPtr class


[List](../list/) pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<T0>
```

## Методы

| Метод | Описание |
| --- | --- |
| [ListPtr](./listptr/)(std::nullptr_t) | Инициализирует нулевой указатель. |
| [ListPtr](./listptr/)(const SharedPtr\<List\<T\>\>\&) | Инициализирует указатель на указанный список. |
| [operator==](./operator==/)(std::nullptr_t) const | Проверяет, является ли указатель [List](../list/) нулевым. |
| [operator[]](./operator[]/)(int) | Аксессор. |
| [operator[]](./operator[]/)(int) const | Аксессор. |
## См. также

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
