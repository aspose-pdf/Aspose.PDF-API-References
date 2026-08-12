---
title: "System::IO::BinaryReader::Read método"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BinaryReader::Read método. Lee un solo carácter del flujo de entrada en C++."
type: docs
weight: 700
url: /es/cpp/system.io/binaryreader/read/
---
## BinaryReader::Read() method


Lee un solo carácter del flujo de entrada.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### ReturnValue

Leer carácter codificado con codificación UTF-16; si el carácter leído está representado por dos puntos de código en la codificación UTF-16, entonces solo se devuelve el surragate alto.

## Ver también

* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) method


Lee la cantidad especificada de caracteres del flujo de entrada, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en la matriz de caracteres especificada comenzando en la posición indicada.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArrayPtr\<char_t\> | La matriz de caracteres UTF-16 donde escribir los caracteres leídos del flujo de entrada |
| índice | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de caracteres a leer del flujo |

### ReturnValue

El número de caracteres leídos del flujo de entrada

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) method


Lee la cantidad especificada de bytes del flujo de entrada y los escribe en la matriz de bytes especificada.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArrayPtr\<uint8_t\> | La matriz de bytes para escribir los bytes leídos |
| índice | int | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de bytes a leer |

### ReturnValue

El número de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
