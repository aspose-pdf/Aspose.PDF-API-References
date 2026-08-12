---
title: "System::Threading::Interlocked::Exchange método"
linktitle: "Exchange"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Interlocked::Exchange método. Intercambia el valor en la variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo en C++."
type: docs
weight: 400
url: /es/cpp/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) method


Intercambia el valor en la variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de variable. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia a la variable para cambiar. |
| valor | T | Valor a almacenar. |

### ReturnValue

Valor de la variable justo antes de que se cambiara.

## Ver también

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::Exchange(T\&, T) method


Intercambia el valor en la variable: almacena el nuevo valor y devuelve el valor que la variable tenía inmediatamente antes de almacenarlo. No implementado.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de variable. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia a la variable para cambiar. |
| valor | T | Valor a almacenar. |

### ReturnValue

Valor de la variable justo antes de que se cambiara.

## Ver también

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
