---
title: "Método System::MakeYieldEnumerator"
linktitle: "CrearEnumeradorConYield"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::MakeYieldEnumerator. Crea un IEnumerator a partir de una función yield en C++."
type: docs
weight: 26200
url: /es/cpp/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator method


Crea un IEnumerator a partir de una función yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en la secuencia |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | La función yield a ejecutar |

### ReturnValue

Puntero compartido al IEnumerator

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
