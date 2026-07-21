---
title: "System::Linq::IOrderedEnumerable clase"
linktitle: "IOrderedEnumerable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Linq::IOrderedEnumerable clase. Representa una secuencia ordenada en C++."
type: docs
weight: 300
url: /es/cpp/system.linq/iorderedenumerable/
---
## IOrderedEnumerable class


Representa una secuencia ordenada.

```cpp
template<typename T>class IOrderedEnumerable : public System::Collections::Generic::IEnumerable<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos de la secuencia. |
## Métodos

| Método | Descripción |
| --- | --- |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador. |
| [IOrderedEnumerable](./iorderedenumerable/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&, const Comparator\&) |  |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<T, Key\>\&) | Realiza una ordenación posterior de los elementos en una secuencia en orden ascendente según una clave. |
| [LINQ_ThenBy](./linq_thenby/)(const Func\<Source, Key\>\&) |  |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Comparator](./comparator/) | Información RTTI. |

## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Linq](../)
* Library [Aspose.PDF for C++](../../)
