---
title: "Класс System::Collections::Generic::SortedDictionaryPtr"
linktitle: "SortedDictionaryPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::SortedDictionaryPtr. Указатель на отсортированный словарь с операторами доступа. Этот тип является указателем для управления удалением других объектов. Его следует выделять в стеке и передавать в функции либо по значению, либо по константной ссылке в C++."
type: docs
weight: 4100
url: /ru/cpp/system.collections.generic/sorteddictionaryptr/
---
## SortedDictionaryPtr class


Указатель на отсортированный словарь с операторами доступа. Этот тип представляет собой указатель для управления удалением другого объекта. Он должен быть выделен в стеке и передаваться в функции по значению или по константной ссылке.

```cpp
template<typename T,typename V>class SortedDictionaryPtr : public System::SmartPtr<T0>
```

## Методы

| Метод | Описание |
| --- | --- |
| [operator[]](./operator[]/)(const T\&) const | Функция доступа. |
| [SortedDictionaryPtr](./sorteddictionaryptr/)() | Создаёт нулевой указатель. |
| [SortedDictionaryPtr](./sorteddictionaryptr/)(const SharedPtr\<SortedDictionary\<T, V\>\>\&) | Создаёт указатель на указанный отсортированный словарь. |
## См. также

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
