---
title: "System::Linq::IOrderedEnumerable::LINQ_ThenBy método"
linktitle: "LINQ_ThenBy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método LINQ_ThenBy de la clase System::Linq::IOrderedEnumerable en C++."
type: docs
weight: 300
url: /es/cpp/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Realiza una ordenación posterior de los elementos en una secuencia en orden ascendente según una clave.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


| Parámetro | Descripción |
| --- | --- |
| Clave | El tipo de la clave devuelta por keySelector. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keySelector | const Func\<T, Key\>\& | Una función para extraer una clave de cada elemento. |

### ReturnValue

[System::Linq::IOrderedEnumerable](../) whose elements are sorted according to a key.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
