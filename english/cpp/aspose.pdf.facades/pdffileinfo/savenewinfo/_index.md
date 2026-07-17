---
title: Aspose::Pdf::Facades::PdfFileInfo::SaveNewInfo method
linktitle: SaveNewInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileInfo::SaveNewInfo method. Save updated PDF document into specified stream in C++.'
type: docs
weight: 3300
url: /cpp/aspose.pdf.facades/pdffileinfo/savenewinfo/
---
## PdfFileInfo::SaveNewInfo(const System::SharedPtr\<System::IO::Stream\>\&) method


Save updated PDF document into specified stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileInfo::SaveNewInfo(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Output stream. |

### ReturnValue

True if success otherwise is false.

## Deprecated
Use Save(destination) method for saving facade results. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileInfo](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileInfo::SaveNewInfo(const System::String\&) method


Save updated PDF document into specified file.

```cpp
bool Aspose::Pdf::Facades::PdfFileInfo::SaveNewInfo(const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | const System::String\& | Output file. |

### ReturnValue

True if success otherwise is false.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileInfo](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
