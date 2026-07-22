---
title: "System::SmartPtr::operator[]‑metod"
linktitle: "operator[]"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SmartPtr::operator[]‑metod. Åtkomstfunktion för array‑element. Kompileras endast om SmartPtr_ är en specialisering av System::Array i C++."
type: docs
weight: 3000
url: /sv/cpp/system/smartptr/operator[]/
---
## SmartPtr::operator[] method


Åtkomstfunktion för array‑element. Kompileras endast om [SmartPtr_](../smartptr_/) är en specialisering av [System::Array](../../array/).

```cpp
template<typename IdxType> decltype(System::Details::GetByIndex(std::declval<const SmartPtr_ *>(), std::declval<IdxType>())) System::SmartPtr<T>::operator[](IdxType idx) const
```


| Parameter | Beskrivning |
| --- | --- |
| IdxType | Typ av index (antagen som heltal). |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| idx | IdxType | [Index](../../index/) i array. |

### ReturnValue

[Array](../../array/) value at idx position.

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
