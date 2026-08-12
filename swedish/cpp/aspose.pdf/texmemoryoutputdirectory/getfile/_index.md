---
title: "Aspose::Pdf::TeXMemoryOutputDirectory::GetFile metod"
linktitle: "GetFile"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::TeXMemoryOutputDirectory::GetFile metod. Returnerar strömmen att läsa från i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf/texmemoryoutputdirectory/getfile/
---
## TeXMemoryOutputDirectory::GetFile method


Returnerar strömmen att läsa från.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::TeXMemoryOutputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | System::String | Filnamnet. |
| fullName | System::String\& | Det fullständiga filnamnet. |
| searchSubdirectories | bool | Indikerar om en fil ska sökas i underkataloger. I denna implementation har den ingen effekt. |

### ReturnValue

Strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TeXMemoryOutputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
