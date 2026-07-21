---
title: "Método System::Collections::Generic::IEnumerable::LINQ_GroupBy"
linktitle: "LINQ_GroupBy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método LINQ_GroupBy de la clase System::Collections::Generic::IEnumerable en C++."
type: docs
weight: 1800
url: /es/cpp/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) method




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) method


Agrupa los elementos de una secuencia.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


| Parámetro | Descripción |
| --- | --- |
| Clave | El tipo de la clave devuelta por keyPredicate |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keyPredicate | System::Func\<T, Key\> | Una función para extraer la clave de cada elemento. |

### ReturnValue

Un [IEnumerable](../) que contiene una secuencia de objetos y una clave

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) method


Agrupa los elementos de una secuencia.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


| Parámetro | Descripción |
| --- | --- |
| Clave | El tipo de la clave devuelta por keyPredicate |
| Elemento | El tipo del elemento devuelto por elementSelector |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keyPredicate | System::Func\<T, Key\> | Una función para extraer la clave de cada elemento. |
| elementSelector | System::Func\<T, Element\> | Una función para extraer la clave de valor de cada elemento. |

### ReturnValue

Un [IEnumerable](../) que contiene una secuencia de objetos y una clave

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
