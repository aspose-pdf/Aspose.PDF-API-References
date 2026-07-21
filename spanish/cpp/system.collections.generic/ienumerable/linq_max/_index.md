---
title: "System::Collections::Generic::IEnumerable::LINQ_Max método"
linktitle: "LINQ_Max"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método LINQ_Max de la clase System::Collections::Generic::IEnumerable en C++."
type: docs
weight: 2100
url: /es/cpp/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Ver también

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) method


Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor máximo resultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por selector. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Una función de transformación para aplicar a cada elemento. |

### ReturnValue

El valor máximo en la secuencia.

## Ver también

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
