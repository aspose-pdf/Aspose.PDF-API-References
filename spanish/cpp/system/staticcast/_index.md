---
title: "Método System::StaticCast"
linktitle: "StaticCast"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::StaticCast. Realiza una conversión estática en objetos que no son punteros en C++."
type: docs
weight: 43300
url: /es/cpp/system/staticcast/
---
## System::StaticCast(const TFrom\&) method


Realiza una conversión estática en objetos que no son punteros.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo objetivo. |
| TFrom | Tipo origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const TFrom\& | Objeto origen. |

### ReturnValue

Resultado del cast si el cast está permitido.

## Deprecated
Conservado por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(const TFrom\&) method


Realiza una conversión estática de objetos [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de [Exception](../exception/) objetivo. |
| TFrom | Tipo de [Exception](../exception/) origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const TFrom\& | Puntero de origen. |

### ReturnValue

Resultado del cast si el cast está permitido.

## Deprecated
Conservado por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(const TFrom *) method


Especialización para tipos aritméticos.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\> const\&) method


Realiza una conversión estática de objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
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

## Deprecated
Conservado por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\>) method


Realiza una conversión estática de Objects a objetos [Exception](../exception/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de [Exception](../exception/) objetivo. |
| TFrom | Tipo de [Object](../object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Puntero de origen. |

### ReturnValue

Resultado del cast si el cast está permitido.

## Deprecated
Conservado por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(std::nullptr_t) method


Realiza una conversión estática de objetos nulos.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del apuntado objetivo. |

### ReturnValue

nullptr.

## Deprecated
Conservado por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(TFrom) method


Especialización para tipos aritméticos.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(TTo) method


Procesar cast de [String](../string/) a [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## Ver también

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(WeakPtr\<TFrom\> const\&) method


Realiza una conversión estática de objetos [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del apuntado objetivo. |
| TFrom | Tipo del apuntado origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Puntero de origen. |

### ReturnValue

Resultado del cast si el cast está permitido.

## Deprecated
Conservado por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
