---
title: "System::Collections::Generic::operator== метод"
linktitle: "operator=="
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::operator== метод. Сравнивает две пары ключ‑значение, используя семантику ''equals''. Использует оператор == или метод EqualsTo для обоих ключей и значений, в зависимости от того, что определено в C++."
type: docs
weight: 5600
url: /ru/cpp/system.collections.generic/operator==/
---
## System::Collections::Generic::operator== method


Сравнивает две пары ключ‑значение, используя семантику 'equals'. Использует оператор == или метод EqualsTo для обоих ключей и значений, в зависимости от того, что определено.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| лево | const KeyValuePair\\<TKey, TValue\\>\\& | Операнд LHS. |
| право | const KeyValuePair\\<TKey, TValue\\>\\& | Операнд RHS. |

### ReturnValue

Истина, если оба ключа и значения совпадают, иначе ложь.

## См. также

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
