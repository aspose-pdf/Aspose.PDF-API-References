---
title: "System::Threading::Interlocked::CompareExchange método"
linktitle: "CompareExchange"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Interlocked::CompareExchange método. Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado en C++."
type: docs
weight: 200
url: /es/cpp/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) method


Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | int32_t\& | Referencia a la variable para cambiar. |
| valor | int32_t | Valor a almacenar. |
| comparando | int32_t | Valor con el que comparar el valor de la variable antes de intercambiar. |
| exitoso | bool\& | Referencia a la variable que se establece en true si se realizó el intercambio y en false en caso contrario. |

### ReturnValue

Valor de la variable al iniciar la operación, independientemente de si se cambió o no.

## Ver también

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de variable. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia a la variable para cambiar. |
| valor | T | Valor a almacenar. |
| comparando | T | Valor con el que comparar el valor de la variable antes de intercambiar. |

### ReturnValue

Valor de la variable al iniciar la operación, independientemente de si se cambió o no.

## Ver también

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Intercambia y compara el valor en la variable: verifica si la variable es igual a un valor específico y almacena el nuevo valor solo si el valor almacenado coincide con el esperado. No implementado.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de variable. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location1 | T\& | Referencia a la variable para cambiar. |
| valor | T | Valor a almacenar. |
| comparando | T | Valor con el que comparar el valor de la variable antes de intercambiar. |

### ReturnValue

Valor de la variable al iniciar la operación, independientemente de si se cambió o no.

## Ver también

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
