---
title: Aspose::Pdf::ITeXInputDirectory::GetFile method
linktitle: GetFile
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ITeXInputDirectory::GetFile method. Returns the stream to read from or to write to in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/itexinputdirectory/getfile/
---
## ITeXInputDirectory::GetFile method


Returns the stream to read from or to write to.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Pdf::ITeXInputDirectory::GetFile(System::String fileName, System::String &fullName, bool searchSubdirectories=false)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| fileName | System::String | The file name. |
| fullName | System::String\& | The full file name. |
| searchSubdirectories | bool | Indicates whether to look for a file in subdirectories. |

### ReturnValue

The stream.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ITeXInputDirectory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
