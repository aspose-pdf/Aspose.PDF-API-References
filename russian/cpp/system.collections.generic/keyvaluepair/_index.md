---
title: "System::Collections::Generic::KeyValuePair класс"
linktitle: "KeyValuePair"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::KeyValuePair класс. Пара ключа и значения. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа в C++."
type: docs
weight: 2900
url: /ru/cpp/system.collections.generic/keyvaluepair/
---
## KeyValuePair class


Пара ключа и значения. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../../system/smartptr/) для управления объектами этого типа.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Key](./get_key/)() const | Получает ключ. |
| [get_Value](./get_value/)() const | Получает значение. |
| [GetHashCode](./gethashcode/)() const | Вычисляет хеш пары ключ-значение, используя XOR хешей ключа и значения. |
| [IsNull](./isnull/)() const | Всегда возвращает false. |
| [KeyValuePair](./keyvaluepair/)() | Инициализатор нулевой пары ключ-значение. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Конструктор. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Конструктор преобразования типа. |
| [operator<](./operator_/)(const KeyValuePair\&) const | Заплатка для классов, наследующихся от [IComparer<KeyValuePair<TKey, TValue>>](../icomparer/), не сравнивает ничего. |
| [ToString](./tostring/)() const | Преобразует пару ключ-значение в строку. |

## См. также

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
