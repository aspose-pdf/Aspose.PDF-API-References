---
title: Aspose::Pdf::TeXMemoryOutputDirectory::GetFile method
linktitle: GetFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TeXMemoryOutputDirectory::GetFile method. Returns the stream to read from in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/texmemoryoutputdirectory/getfile/
---
## TeXMemoryOutputDirectory::GetFile method


Returns the stream to read from.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::TeXMemoryOutputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| fileName | System::String | The file name. |
| fullName | System::String\& | The full file name. |
| searchSubdirectories | bool | Indicates whether to look for a file in subdirectories. In this implementation has no effect. |

### ReturnValue

The stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [TeXMemoryOutputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
