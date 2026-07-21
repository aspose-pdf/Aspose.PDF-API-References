---
title: "System::ForceStaticCast método"
linktitle: "ForzarConversiónEstática"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ForceStaticCast método. Realiza una conversión estática real en objetos SmartPtr en C++."
type: docs
weight: 20900
url: /es/cpp/system/forcestaticcast/
---
## System::ForceStaticCast method


Realiza una conversión estática real en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del apuntado objetivo. |
| TFrom | Tipo del apuntado origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido; de lo contrario, el comportamiento es indefinido.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
