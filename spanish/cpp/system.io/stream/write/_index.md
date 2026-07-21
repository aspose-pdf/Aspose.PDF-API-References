---
title: "Método System::IO::Stream::Write"
linktitle: "Write"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::Stream::Write. Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo en C++."
type: docs
weight: 2600
url: /es/cpp/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


| Parámetro | Descripción |
| --- | --- |
| N | El tamaño de la matriz de pila |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::StackArray\<uint8_t, N\>\& | El array de pila que contiene los bytes a escribir. |
| desplazamiento | int32_t | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method


Escribe el subrango especificado de bytes del span de bytes especificado en el flujo.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::ReadOnlySpan\<uint8_t\>\& | El span de bytes del cual leer los bytes escritos. |

## Ver también

* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
