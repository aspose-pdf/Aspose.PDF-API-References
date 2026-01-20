---
title: Aspose::Pdf::Facades::PdfFileMend::AddImage method
linktitle: AddImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileMend::AddImage method. Adds image to the specified page of PDF document at specified coordinates in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.facades/pdffilemend/addimage/
---
## PdfFileMend::AddImage(System::SharedPtr\<System::IO::Stream\>, int32_t, float, float, float, float) method


Adds image to the specified page of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::SharedPtr<System::IO::Stream> imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | System::SharedPtr\<System::IO::Stream\> | Input image stream. |
| pageNum | int32_t | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

### ReturnValue

True if success false otherwise.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(System::SharedPtr\<System::IO::Stream\>, int32_t, float, float, float, float, System::SharedPtr\<CompositingParameters\>) method


Adds image to the specified page of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::SharedPtr<System::IO::Stream> imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, System::SharedPtr<CompositingParameters> compositingParameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | System::SharedPtr\<System::IO::Stream\> | Input image stream. |
| pageNum | int32_t | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | System::SharedPtr\<CompositingParameters\> | The graphics compositing parameters for the image. |

### ReturnValue

True if success false otherwise.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, float, float, float, float) method


Adds image to the specified pages of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::SharedPtr<System::IO::Stream> imageStream, System::ArrayPtr<int32_t> pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | System::SharedPtr\<System::IO::Stream\> | Input image stream. |
| pageNums | System::ArrayPtr\<int32_t\> | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

### ReturnValue

True if success false otherwise.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, float, float, float, float, System::SharedPtr\<CompositingParameters\>) method


Adds image to the specified pages of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::SharedPtr<System::IO::Stream> imageStream, System::ArrayPtr<int32_t> pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, System::SharedPtr<CompositingParameters> compositingParameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | System::SharedPtr\<System::IO::Stream\> | Input image stream. |
| pageNums | System::ArrayPtr\<int32_t\> | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | System::SharedPtr\<CompositingParameters\> | The graphics compositing parameters for the images. |

### ReturnValue

True if success false otherwise.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(System::String, int32_t, float, float, float, float) method


Adds image to the specified page of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::String imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageName | System::String | The path of input image file. |
| pageNum | int32_t | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

### ReturnValue

True if success false otherwise.

## See Also

* Class [String](../../../system/string/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(System::String, int32_t, float, float, float, float, System::SharedPtr\<CompositingParameters\>) method


Adds image to the specified page of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::String imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, System::SharedPtr<CompositingParameters> compositingParameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageName | System::String | The path of input image file. |
| pageNum | int32_t | The number of page that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | System::SharedPtr\<CompositingParameters\> | The graphics compositing parameters for the images. |

### ReturnValue

True if success false otherwise.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(System::String, System::ArrayPtr\<int32_t\>, float, float, float, float) method


Adds image to the specified pages of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::String imageName, System::ArrayPtr<int32_t> pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageName | System::String | The path of input image file. |
| pageNums | System::ArrayPtr\<int32_t\> | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |

### ReturnValue

True if success false otherwise.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(System::String, System::ArrayPtr\<int32_t\>, float, float, float, float, System::SharedPtr\<CompositingParameters\>) method


Adds image to the specified pages of PDF document at specified coordinates.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(System::String imageName, System::ArrayPtr<int32_t> pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, System::SharedPtr<CompositingParameters> compositingParameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageName | System::String | The path of input image file. |
| pageNums | System::ArrayPtr\<int32_t\> | The numbers of pages that will receive the image. |
| lowerLeftX | float | The lower left x of image rectangle. |
| lowerLeftY | float | The lower left y of image rectangle. |
| upperRightX | float | The upper right x of image rectangle. |
| upperRightY | float | The upper right y of image rectangle. |
| compositingParameters | System::SharedPtr\<CompositingParameters\> | The graphics compositing parameters for the images. |

### ReturnValue

True if success false otherwise.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
