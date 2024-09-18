---
title: Aspose::Pdf::Facades::PdfExtractor::GetAttachment method
linktitle: GetAttachment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfExtractor::GetAttachment method. Stores attachment into file in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf.facades/pdfextractor/getattachment/
---
## PdfExtractor::GetAttachment(System::String) method


Stores attachment into file.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfExtractor::GetAttachment(System::String outputPath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputPath | System::String | Directory path where attachment(s) will be stored. Null or empty string means attachment(s) will be placed in the application directory. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputPath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Directory path where attachment(s) will be stored. Null or empty string means attachment(s) will be placed in the application directory. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetAttachment() method


Saves all the attachment file to streams.

```cpp
ASPOSE_PDF_SHARED_API System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfExtractor::GetAttachment()
```


### ReturnValue

The stream array of the attachment file in the pdf document.

## See Also

* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
