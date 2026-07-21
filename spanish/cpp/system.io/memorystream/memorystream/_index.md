---
title: "System::IO::MemoryStream::MemoryStream constructor"
linktitle: "MemoryStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::IO::MemoryStream::MemoryStream. Construye una nueva instancia de la clase MemoryStream con una capacidad inicial igual a 0 en C++."
type: docs
weight: 100
url: /es/cpp/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() constructor


Construye una nueva instancia de la clase [MemoryStream](../) con una capacidad inicial igual a 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## Ver también

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) constructor


Construye una nueva instancia de la clase [MemoryStream](../) que representa un flujo de memoria conectado al búfer de memoria especificado. Un parámetro indica si el flujo es escribible.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=true)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | const ArrayPtr\<uint8_t\>\& | Una matriz de bytes que se usará como búfer de memoria sobre el cual se basará el flujo representado por el objeto que se está creando |
| escribible | bool | Especifica si el flujo debe ser escribible |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) constructor


Construye una nueva instancia de la clase [MemoryStream](../) que representa un flujo de memoria conectado a un segmento del búfer de memoria especificado, comenzando en el índice especificado e incluyendo el número especificado de elementos. Los parámetros indican si el flujo es escribible y si se puede llamar al método GetBytes().

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=true, bool publiclyVisible=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | const ArrayPtr\<uint8_t\>\& | Una matriz de bytes, cuyo segmento se usará como búfer de memoria sobre el cual se basará el flujo representado por el objeto que se está creando |
| índice | int | Un índice basado en 0 del elemento en **content** donde comienza el segmento |
| count | int | El número de elementos de **content** incluidos en el segmento |
| escribible | bool | Especifica si el flujo debe ser escribible |
| publiclyVisible | bool | Especifica si el búfer de memoria subyacente debe estar disponible para el llamador del método GetByte() |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## MemoryStream::MemoryStream(int) constructor


Construye una nueva instancia de la clase [MemoryStream](../) que representa un flujo basado en un búfer de memoria del tamaño especificado.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capacity_ | int | El tamaño en bytes de un búfer de memoria asociado al flujo representado por el objeto que se está creando |

## Ver también

* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
