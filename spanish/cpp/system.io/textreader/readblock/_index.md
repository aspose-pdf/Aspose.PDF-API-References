---
title: "System::IO::TextReader::ReadBlock método"
linktitle: "ReadBlock"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::TextReader::ReadBlock método. Lee el número máximo especificado de caracteres del lector de texto actual y escribe los datos en un búfer, comenzando en el índice especificado en C++."
type: docs
weight: 500
url: /es/cpp/system.io/textreader/readblock/
---
## TextReader::ReadBlock method


Lee la cantidad máxima especificada de caracteres del lector de texto actual y escribe los datos en un búfer, comenzando en el índice especificado.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArrayPtr\<char_t\> | Un búfer de caracteres donde escribir los datos leídos |
| índice | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número máximo de caracteres a leer |

### ReturnValue

El número real de caracteres leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
