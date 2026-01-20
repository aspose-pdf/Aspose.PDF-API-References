---
title: Aspose::Pdf::Facades::PdfExtractor::GetAttachment method
linktitle: GetAttachment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfExtractor::GetAttachment method. Saves all the attachment file to streams in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.facades/pdfextractor/getattachment/
---
## PdfExtractor::GetAttachment() method


Saves all the attachment file to streams.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfExtractor::GetAttachment()
```


### ReturnValue

The stream array of the attachment file in the pdf document.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetAttachment(System::String) method


Stores attachment into file.

```cpp
void Aspose::Pdf::Facades::PdfExtractor::GetAttachment(System::String outputPath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputPath | System::String | Directory path where attachment(s) will be stored. Null or empty string means attachment(s) will be placed in the application directory. |

## See Also

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
