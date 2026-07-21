---
title: "Constructor System::ExceptionWrapper::ExceptionWrapper"
linktitle: "ExceptionWrapper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::ExceptionWrapper::ExceptionWrapper. Constructor que reenvía los parámetros a los constructores de la clase Exception y crea un puntero inteligente que contiene una nueva instancia de la clase Exception en C++."
type: docs
weight: 100
url: /es/cpp/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor


Constructor que reenvía los parámetros a los constructores de la clase [Exception](../../exception/) y crea un puntero inteligente que contiene una nueva instancia de la clase [Exception](../../exception/).

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Ver también

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor


Construye una instancia de la clase [ExceptionWrapper](../) que contiene el puntero pasado.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const ExceptionPtr\& | Puntero inteligente a la instancia de la clase [Exception](../../exception/). |

## Ver también

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor


Constructor de copia.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const ExceptionWrapper\& | Otra instancia de la clase wrapper que debe ser copiada. |

## Ver también

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor


Constructor de movimiento.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | ExceptionWrapper\&& | Otra instancia de la clase wrapper que debe ser movida. |

## Ver también

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor


Construye una instancia nula de la clase [ExceptionWrapper](../) que no representa ninguna excepción.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## Ver también

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
