---
title: "System::Net::Sockets::NetworkStream::Write método"
linktitle: "Write"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::NetworkStream::Write método. Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo en C++."
type: docs
weight: 2500
url: /es/cpp/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | El arreglo que contiene los bytes a escribir. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de elementos en el subrango a escribir. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| size | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
