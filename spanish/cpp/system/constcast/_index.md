---
title: "Método System::ConstCast"
linktitle: "ConstCast"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ConstCast. Fin de los casts obsoletos en C++."
type: docs
weight: 16600
url: /es/cpp/system/constcast/
---
## System::ConstCast method


Fin de los casts obsoletos.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del apuntado objetivo. |
| TFrom | Tipo del apuntado origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<TFrom\>\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.
## Observaciones


Realiza un cast const en objetos [SmartPtr](../smartptr/).
## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
