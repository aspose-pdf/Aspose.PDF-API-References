---
title: "Метод System::SmartPtr::operator[]"
linktitle: "operator[]"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::SmartPtr::operator[]. Доступ к элементам массива. Компилируется только если SmartPtr_ является специализацией System::Array в C++."
type: docs
weight: 3000
url: /ru/cpp/system/smartptr/operator[]/
---
## SmartPtr::operator[] method


Доступ к элементам массива. Компилируется только если [SmartPtr_](../smartptr_/) является специализацией [System::Array](../../array/).

```cpp
template<typename IdxType> decltype(System::Details::GetByIndex(std::declval<const SmartPtr_ *>(), std::declval<IdxType>())) System::SmartPtr<T>::operator[](IdxType idx) const
```


| Параметр | Описание |
| --- | --- |
| IdxType | Тип индекса (предполагается целочисленный). |

| Параметр | Тип | Описание |
| --- | --- | --- |
| idx | IdxType | [Index](../../index/) в массиве. |

### ReturnValue

[Array](../../array/) value at idx position.

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
