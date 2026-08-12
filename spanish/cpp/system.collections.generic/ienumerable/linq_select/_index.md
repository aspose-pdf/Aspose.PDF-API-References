---
title: "System::Collections::Generic::IEnumerable::LINQ_Select método"
linktitle: "LINQ_Select"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método LINQ_Select de la clase System::Collections::Generic::IEnumerable en C++."
type: docs
weight: 2700
url: /es/cpp/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method


Transforma cada elemento de una secuencia en una nueva forma incorporando el índice del elemento.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por el **selector**. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const Func\<T, int32_t, ResultType\>\& | Una función de transformación. |

### ReturnValue

Un [IEnumerable](../) que contiene los elementos devueltos por la función **selector**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method


Transforma los elementos de una secuencia.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por el **selector**. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Una función de transformación. |

### ReturnValue

Un [IEnumerable](../) que contiene los elementos devueltos por la función **selector**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
