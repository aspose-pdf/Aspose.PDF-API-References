---
title: "Método System::AsCast"
linktitle: "AsCast"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::AsCast. Convierte el tipo de origen al tipo de resultado usando el operador de conversión ''as''. Se usa cuando se necesita una conversión simple similar a un constructor en C++."
type: docs
weight: 14000
url: /es/cpp/system/ascast/
---
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa cuando se necesita una conversión simple similar a un constructor.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa cuando el tipo de origen y el tipo de resultado son iguales.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión.

## Ver también

* Enum [Base64FormattingOptions](../base64formattingoptions/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para envoltorios de excepciones.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión. Devuelve nullptr si no hay conversión disponible.

## Ver también

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para convertir un objeto a excepción.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión. Devuelve nullptr si no hay conversión disponible.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa cuando tanto el origen como el resultado son punteros inteligentes.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión. Devuelve nullptr si no hay conversión disponible.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa cuando tanto el origen como el resultado son punteros inteligentes (con [SmartPtr<...>](../smartptr/) explícito en el tipo de resultado).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión. Devuelve nullptr si no hay conversión disponible.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para desempaquetar un objeto a nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión. Devuelve un nullable vacío si no hay conversión disponible.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Desempaquetado inválido a un tipo que no es objeto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

Siempre devuelve null.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Desempaquetado inválido a un tipo que no es objeto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

Siempre devuelve null.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para empaquetar un objeto nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para empaquetar un objeto común.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para empaquetar un objeto común.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para desempaquetar una cadena.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para el caso de nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Convierte el tipo de origen al tipo de resultado usando el operador ''as''. Se usa para convertir entre matrices.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parámetro | Descripción |
| --- | --- |
| Origen | El tipo de origen. |
| Result | El tipo de resultado. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### ReturnValue

El resultado de la conversión. Devuelve nullptr si no hay conversión disponible para ningún elemento de la matriz.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
