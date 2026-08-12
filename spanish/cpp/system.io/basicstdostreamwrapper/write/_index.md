---
title: "System::IO::BasicSTDOStreamWrapper::Write método"
linktitle: "Write"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BasicSTDOStreamWrapper::Write método. Si el modo de envoltura es binario, escribe en el flujo el subrango especificado de bytes del arreglo de bytes especificado; de lo contrario, convierte el subrango especificado de bytes del arreglo de bytes especificado al tipo char_type y luego escribe el resultado en el flujo en C++."
type: docs
weight: 700
url: /es/cpp/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Si el modo de envoltura es binario, escribe en el flujo el subrango especificado de bytes del arreglo de bytes especificado; de lo contrario, convierte el subrango especificado de bytes del arreglo de bytes especificado al tipo [char_type](../char_type/) y luego escribe el resultado en el flujo.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
