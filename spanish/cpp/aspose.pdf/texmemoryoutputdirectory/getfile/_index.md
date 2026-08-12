---
title: "Aspose::Pdf::TeXMemoryOutputDirectory::GetFile método"
linktitle: "GetFile"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::TeXMemoryOutputDirectory::GetFile método. Devuelve el flujo para leer en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf/texmemoryoutputdirectory/getfile/
---
## TeXMemoryOutputDirectory::GetFile method


Devuelve el flujo de lectura.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::TeXMemoryOutputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | System::String | El nombre del archivo. |
| fullName | System::String\& | El nombre completo del archivo. |
| searchSubdirectories | bool | Indica si se debe buscar un archivo en subdirectorios. En esta implementación no tiene efecto. |

### ReturnValue

El flujo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TeXMemoryOutputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
