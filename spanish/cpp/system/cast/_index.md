---
title: "System::Cast método"
linktitle: "Cast"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Cast método. Realiza una conversión en objetos SmartPtr en C++."
type: docs
weight: 15800
url: /es/cpp/system/cast/
---
## System::Cast method


Realiza una conversión en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del apuntado objetivo. |
| TFrom | Tipo del apuntado origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Puntero de origen. |

### ReturnValue

Resultado del cast si el cast está permitido.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
