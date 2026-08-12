---
title: "System::IO::BasicSTDOStreamWrapper::Read método"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BasicSTDOStreamWrapper::Read método. Si el modo de envoltura es binario, lee la cantidad especificada de bytes del flujo; de lo contrario, lee la cantidad especificada de caracteres y los convierte al tipo uint8_t. Escribe el resultado de la lectura en el arreglo de bytes especificado. ¡No soportado! en C++."
type: docs
weight: 400
url: /es/cpp/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Si el modo de envoltura es binario, lee la cantidad especificada de bytes del flujo; de lo contrario, lee la cantidad especificada de caracteres y los convierte al tipo uint8_t. Escribe el resultado de la lectura en la matriz de bytes especificada. ¡No soportado!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz de bytes para escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

Número de bytes o caracteres leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const System::Details::ArrayView\<uint8_t\>\& | La vista del arreglo de bytes a la que escribir los bytes leídos |
| desplazamiento | int32_t | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int32_t | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
