---
title: "System::IO::MemoryStream::TryGetBuffer método"
linktitle: "TryGetBuffer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::MemoryStream::TryGetBuffer método. Devuelve la matriz de bytes sin signo a partir de la cual se creó este stream en C++."
type: docs
weight: 1800
url: /es/cpp/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer method


Devuelve la matriz de bytes sin signo a partir de la cual se creó este flujo.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | ArraySegment\<uint8_t\>\& | matriz de bytes - parámetro de salida. Cuando este método devuelve true, el segmento de matriz de bytes del cual se creó este stream; cuando devuelve false, este parámetro se establece a su valor predeterminado. |

### ReturnValue

True si la conversión tuvo éxito.

## Ver también

* Class [ArraySegment](../../../system/arraysegment/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
