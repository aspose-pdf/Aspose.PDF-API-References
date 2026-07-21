---
title: "System::Cast_noexcept método"
linktitle: "Cast_noexcept"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Cast_noexcept método. Realiza una conversión en objetos SmartPtr en C++."
type: docs
weight: 15900
url: /es/cpp/system/cast_noexcept/
---
## System::Cast_noexcept method


Realiza una conversión en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del apuntado objetivo. |
| TFrom | Tipo del apuntado origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
