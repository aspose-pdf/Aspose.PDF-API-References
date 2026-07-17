---
title: Aspose::Pdf::Facades::PdfExtractor::GetNextImage method
linktitle: GetNextImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfExtractor::GetNextImage method. Retrieve next image from PDF file and stores it into stream in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.facades/pdfextractor/getnextimage/
---
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&) method


Retrieve next image from PDF file and stores it into stream.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream where image data will be saved |

### ReturnValue

True in case the image is successfully extracted.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Retrieve next image from PDF file and stores it into stream with given image format.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream where image data will be saved |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | The format of the image. |

### ReturnValue

True in case the image is successfully extracted.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&) method


Retrieves next image from PDF document. [Note](../../../aspose.pdf/note/): ExtractImage must be called before using of this method.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | const System::String\& | File where image will be stored |

### ReturnValue

True is image is successfully extracted

## See Also

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Retrieves next image from PDF document with given image format. [Note](../../../aspose.pdf/note/): ExtractImage must be called before using of this method.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | const System::String\& | File where image will be stored |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | The format of the image. |

### ReturnValue

True is image is successfully extracted

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
