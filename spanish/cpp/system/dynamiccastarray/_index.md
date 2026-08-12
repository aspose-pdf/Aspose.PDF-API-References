---
title: "Método System::DynamicCastArray"
linktitle: "DynamicCastArray"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::DynamicCastArray. Realiza la conversión de los elementos del arreglo especificado a un tipo diferente en C++."
type: docs
weight: 18400
url: /es/cpp/system/dynamiccastarray/
---
## System::DynamicCastArray method


Realiza la conversión de los elementos del arreglo especificado a un tipo diferente.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que convertir los elementos del array especificado |
| From | El tipo de los elementos del array cuyos elementos se van a convertir |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| desde | const SharedPtr\<Array\<From\>\>\& | Puntero compartido al array que contiene los elementos a convertir |

### ReturnValue

Un puntero a un nuevo array que contiene elementos del tipo **To** equivalentes a los elementos de **from**

## Deprecated
Añadido por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
