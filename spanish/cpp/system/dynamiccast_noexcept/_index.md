---
title: "Método System::DynamicCast_noexcept"
linktitle: "DynamicCast_noexcept"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::DynamicCast_noexcept. Conversiones antiguas obsoletas. Será eliminado en versiones futuras en C++."
type: docs
weight: 18100
url: /es/cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) method


Conversiones antiguas obsoletas. Será eliminado en versiones futuras.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de [Exception](../exception/) objetivo. |
| TFrom | Tipo de [Exception](../exception/) origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const TFrom\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.
## Observaciones


Realiza cast dinámico en objetos [Exception](../exception/). ## Obsoleto
Mantenido por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) method


Realiza cast dinámico en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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

## Deprecated
Mantenido por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) method


Realiza cast dinámico en objetos a objetos [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de [Exception](../exception/) objetivo. |
| TFrom | Tipo de [Object](../object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.

## Deprecated
Mantenido por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
