---
title: "System::Collections::Generic::IEnumerable::LINQ_SelectMany método"
linktitle: "LINQ_SelectMany"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método LINQ_SelectMany de la clase System::Collections::Generic::IEnumerable en C++."
type: docs
weight: 2800
url: /es/cpp/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Proyecta cada elemento de una secuencia y combina las secuencias resultantes en una sola secuencia.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por el **selector**. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\& | Una función de transformación. |

### ReturnValue

Un [IEnumerable](../) que contiene el resultado de invocar una función de proyección de uno a muchos en cada elemento de la secuencia de entrada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
