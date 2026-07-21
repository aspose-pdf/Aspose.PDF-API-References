---
title: "Método System::IO::BasicSTDIStreamWrapper::Write"
linktitle: "Write"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::BasicSTDIStreamWrapper::Write. Si el modo de encapsulado es binario, escribe en el flujo el subrango especificado de bytes del arreglo de bytes indicado; de lo contrario, convierte el subrango especificado de bytes del arreglo indicado al tipo char_type y luego escribe el resultado en el flujo. ¡No soportado! en C++."
type: docs
weight: 700
url: /es/cpp/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Si el modo de encapsulado es binario, escribe en el flujo el subrango especificado de bytes del arreglo de bytes indicado; de lo contrario, convierte el subrango especificado de bytes del arreglo indicado al tipo [char_type](../char_type/) y luego escribe el resultado en el flujo. ¡No soportado!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | El arreglo que contiene los bytes a escribir. |
| desplazamiento | int32_t | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir. |
| count | int32_t | El número de elementos en el subrango a escribir. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Escribe el subrango especificado de bytes de la matriz de bytes especificada al flujo.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo que contiene los bytes a escribir |
| desplazamiento | int32_t | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | int32_t | El número de elementos en el subrango a escribir |

## Ver también

* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
