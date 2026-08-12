---
title: "Método System::GetHashCode"
linktitle: "ObtenerCódigoHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::GetHashCode. Especialización para std::thread::id; devuelve el código hash para el objeto de hilo especificado en C++."
type: docs
weight: 21900
url: /es/cpp/system/gethashcode/
---
## System::GetHashCode(const std::thread::id\&) method


Especialización para std::thread::id; devuelve el código hash para el objeto de hilo especificado.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Devuelve un código hash para el valor escalar especificado.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del valor para el cual la función genera el código hash |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | El valor para generar el código hash |

### ReturnValue

El código hash generado para el valor especificado

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Devuelve un código hash para el objeto especificado.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto para el cual la función genera el código hash |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | El [SmartPtr](../smartptr/) que apunta al objeto para generar el código hash |

### ReturnValue

El código hash generado para el objeto especificado

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Devuelve un código hash para el objeto especificado que es una excepción.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto para el cual la función genera el código hash |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | El [Exception](../exception/) envoltorio que contiene el objeto para generar el código hash |

### ReturnValue

El código hash generado para el objeto especificado

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Devuelve un código hash para el objeto especificado que no es un smart pointer ni una excepción.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto para el cual la función genera el código hash |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Una referencia const al objeto para generar el código hash |

### ReturnValue

El código hash generado para el objeto especificado

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
