---
title: "Método System::IO::BufferedStream::Read"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::BufferedStream::Read. Lee la cantidad especificada de bytes del flujo subyacente y los escribe en el arreglo de bytes especificado en C++."
type: docs
weight: 900
url: /es/cpp/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo subyacente y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
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
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo subyacente y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La matriz de bytes para escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
