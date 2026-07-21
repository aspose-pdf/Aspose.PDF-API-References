---
title: "System::IO::BinaryWriter::BinaryWriter constructor"
linktitle: "BinaryWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BinaryWriter::BinaryWriter constructor. Construye una instancia de la clase BinaryWriter que escribe datos en el flujo especificado usando la codificación especificada en C++."
type: docs
weight: 100
url: /es/cpp/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter constructor


Construye una instancia de la clase [BinaryWriter](../) que escribe datos en el flujo especificado usando la codificación especificada.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const StreamPtr\& | El flujo de salida |
| encoding | const EncodingPtr\& | La codificación a usar |
| leaveopen | bool | Especifica si el flujo **stream** debe permanecer abierto (true) después de que el objeto actual haya sido eliminado o no (false) |

## Ver también

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
