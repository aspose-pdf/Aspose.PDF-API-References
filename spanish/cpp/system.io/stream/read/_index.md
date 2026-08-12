---
title: "Método System::IO::Stream::Read"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::Stream::Read. Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado en C++."
type: docs
weight: 1800
url: /es/cpp/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz de bytes para escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo de bytes a la que escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


| Parámetro | Descripción |
| --- | --- |
| N | El tamaño de la matriz de pila |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::StackArray\<uint8_t, N\>\& | El array de pila de bytes donde escribir los bytes leídos. |
| desplazamiento | int32_t | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::Read(const System::Span\<uint8_t\>\&) method


Lee el número especificado de bytes del flujo y los escribe en el span de bytes especificado.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Span\<uint8_t\>\& | El span de bytes donde escribir los bytes leídos. |

### ReturnValue

El número de bytes leídos

## Ver también

* Class [Span](../../../system/span/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
