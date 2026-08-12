---
title: "System::StaticCast_noexcept método"
linktitle: "StaticCast_noexcept"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::StaticCast_noexcept método. Realiza una conversión estática de objetos Exception en C++."
type: docs
weight: 44200
url: /es/cpp/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(const TFrom\&) method


Realiza una conversión estática de objetos [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
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

## Deprecated
Mantenido por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) method


Realiza una conversión estática de objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
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
## System::StaticCast_noexcept(SmartPtr\<TFrom\>) method


Realiza una conversión estática de Objects a objetos [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
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
## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) method


Realiza una conversión estática de objetos [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del apuntado objetivo. |
| TFrom | Tipo del apuntado origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Puntero de origen. |

### ReturnValue

Resultado del casting si el casting está permitido o nullptr en caso contrario.

## Deprecated
Mantenido por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
