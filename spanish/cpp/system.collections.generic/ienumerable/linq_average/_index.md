---
title: "System::Collections::Generic::IEnumerable::LINQ_Average método"
linktitle: "LINQ_Average"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::IEnumerable::LINQ_Average método. Calcula el promedio de una secuencia de valores numéricos en C++."
type: docs
weight: 900
url: /es/cpp/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Calcula el promedio de una secuencia de valores numéricos.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### ReturnValue

El promedio de los valores en la secuencia.

## Ver también

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Ver también

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Calcula el promedio de una secuencia de valores que se obtienen invocando una función de transformación en cada elemento de la secuencia de entrada.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


| Parámetro | Descripción |
| --- | --- |
| ResultType | El tipo del valor devuelto por selector. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Una función de transformación para aplicar a cada elemento. |

### ReturnValue

El promedio de los valores proyectados.

## Ver también

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
