---
title: "Método System::SmartPtr::operator[]"
linktitle: "operator[]"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::SmartPtr::operator[] . Accesor para los elementos del array. Solo se compila si SmartPtr_ es una especialización de System::Array en C++."
type: docs
weight: 3000
url: /es/cpp/system/smartptr/operator[]/
---
## SmartPtr::operator[] method


Accesor para los elementos del array. Solo se compila si [SmartPtr_](../smartptr_/) es una especialización de [System::Array](../../array/).

```cpp
template<typename IdxType> decltype(System::Details::GetByIndex(std::declval<const SmartPtr_ *>(), std::declval<IdxType>())) System::SmartPtr<T>::operator[](IdxType idx) const
```


| Parámetro | Descripción |
| --- | --- |
| IdxType | Tipo de índice (asumido integral). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| idx | IdxType | [Index](../../index/) en matriz. |

### ReturnValue

[Array](../../array/) value at idx position.

## Ver también

* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
