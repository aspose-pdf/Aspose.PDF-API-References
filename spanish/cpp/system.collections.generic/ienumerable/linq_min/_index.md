---
title: "System::Collections::Generic::IEnumerable::LINQ_Min método"
linktitle: "LINQ_Min"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el método LINQ_Min de la clase System::Collections::Generic::IEnumerable en C++."
type: docs
weight: 2200
url: /es/cpp/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Ver también

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


Invoca una función de transformación en cada elemento de una secuencia genérica y devuelve el valor mínimo resultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por selector. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Una función de transformación para aplicar a cada elemento. |

### ReturnValue

El valor mínimo en la secuencia.

## Ver también

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
