---
title: Aspose::Pdf::Facades::PdfExtractor::GetNextImage method
linktitle: GetNextImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfExtractor::GetNextImage method. Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf.facades/pdfextractor/getnextimage/
---
## PdfExtractor::GetNextImage(System::String) method


Retrieves next image from PDF document. [Note](../../../aspose.pdf/note/): ExtractImage must be called before using of this method.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | File where image will be stored |

### ReturnValue

True is image is successfully extracted
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>File where image will be stored</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(System::String, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) method


Retrieves next image from PDF document with given image format. [Note](../../../aspose.pdf/note/): ExtractImage must be called before using of this method.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(System::String outputFile, System::SharedPtr<System::Drawing::Imaging::ImageFormat> format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | System::String | File where image will be stored |
| format | System::SharedPtr\<System::Drawing::Imaging::ImageFormat\> | The format of the image. |

### ReturnValue

True is image is successfully extracted
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>File where image will be stored</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The format of the image.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) method


Retrieve next image from PDF file and stores it into stream with given image format.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<System::Drawing::Imaging::ImageFormat> format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Stream where image data will be saved |
| format | System::SharedPtr\<System::Drawing::Imaging::ImageFormat\> | The format of the image. |

### ReturnValue

True in case the image is successfully extracted.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where image data will be saved</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The format of the image.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(System::SharedPtr\<System::IO::Stream\>) method


Retrieve next image from PDF file and stores it into stream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Stream where image data will be saved |

### ReturnValue

True in case the image is successfully extracted.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where image data will be saved</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
