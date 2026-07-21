---
title: "System::IO::MemoryStream::Write método"
linktitle: "Write"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::MemoryStream::Write método. Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo en C++."
type: docs
weight: 1900
url: /es/cpp/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
