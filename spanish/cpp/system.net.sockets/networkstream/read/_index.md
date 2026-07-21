---
title: "System::Net::Sockets::NetworkStream::Read método"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::NetworkStream::Read método. Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado en C++."
type: docs
weight: 1900
url: /es/cpp/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz de bytes donde se escribirán los bytes leídos. |
| desplazamiento | int32_t | El desplazamiento en bytes en la matriz especificada. |
| size | int32_t | El número de bytes a leer. |

### ReturnValue

El número de bytes leídos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo de bytes a la que escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| size | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
