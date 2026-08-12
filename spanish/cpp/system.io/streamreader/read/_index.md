---
title: "Método System::IO::StreamReader::Read"
linktitle: "Read"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::StreamReader::Read. Lee un solo carácter del flujo en C++."
type: docs
weight: 900
url: /es/cpp/system.io/streamreader/read/
---
## StreamReader::Read() method


Lee un solo carácter del flujo.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### ReturnValue

Leer carácter codificado con codificación UTF-16; si el carácter leído está representado por dos puntos de código en la codificación UTF-16, entonces solo se devuelve el surragate alto.

## Ver también

* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::Read(ArrayPtr\<char_t\>, int, int) method


Lee el número especificado de caracteres del flujo, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en la matriz de caracteres especificada, comenzando en la posición indicada.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArrayPtr\<char_t\> | El arreglo de caracteres UTF-16 donde escribir los caracteres leídos del flujo |
| índice | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de caracteres a leer del flujo |

### ReturnValue

El número de caracteres leídos del flujo

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
