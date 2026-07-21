---
title: "Método System::MakeYieldEnumerable"
linktitle: "CrearEnumerableConYield"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::MakeYieldEnumerable. Crea un IEnumerable a partir de una función yield en C++."
type: docs
weight: 26100
url: /es/cpp/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable method


Crea un IEnumerable a partir de una función yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en la secuencia |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | La función yield a ejecutar |

### ReturnValue

Puntero compartido al IEnumerable

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
