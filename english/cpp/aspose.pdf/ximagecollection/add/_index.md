---
title: Aspose::Pdf::XImageCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XImageCollection::Add method. Adds entity to the end of the collection, so entity can be accessed by the last index in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/ximagecollection/add/
---
## XImageCollection::Add(System::SharedPtr\<Aspose::Pdf::BitmapInfo\>) method


Adds entity to the end of the collection, so entity can be accessed by the last index.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(System::SharedPtr<Aspose::Pdf::BitmapInfo> bitmapInfo)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | System::SharedPtr\<Aspose::Pdf::BitmapInfo\> | Object containing array of pixels and bitmap information (Width, Height, PixelFormat). |

### ReturnValue

Name of the added image.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BitmapInfo](../../bitmapinfo/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(System::SharedPtr\<Aspose::Pdf::BitmapInfo\>, Aspose::Pdf::ImageFilterType) method


Adds entity to the end of the collection, so entity can be accessed by the last index.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(System::SharedPtr<Aspose::Pdf::BitmapInfo> bitmapInfo, Aspose::Pdf::ImageFilterType filterType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bitmapInfo | System::SharedPtr\<Aspose::Pdf::BitmapInfo\> | Object containing array of pixels and bitmap information (Width, Height, PixelFormat). |
| filterType | Aspose::Pdf::ImageFilterType | The image filter type. |

### ReturnValue

Name of the added image.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BitmapInfo](../../bitmapinfo/)
* Enum [ImageFilterType](../../imagefiltertype/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(System::SharedPtr\<System::IO::Stream\>) method


Adds entity to the end of the collection, so entity can be accessed by the last index.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(System::SharedPtr<System::IO::Stream> image)
```


| Parameter | Type | Description |
| --- | --- | --- |
| image | System::SharedPtr\<System::IO::Stream\> | Stream containing image data (in JPEG format). |

### ReturnValue

Name of the added image.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::ImageFilterType) method


Adds entity to the end of the collection, so entity can be accessed by the last index.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(System::SharedPtr<System::IO::Stream> image, Aspose::Pdf::ImageFilterType filterType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| image | System::SharedPtr\<System::IO::Stream\> | Stream containing image data. |
| filterType | Aspose::Pdf::ImageFilterType | The image filter type. |

### ReturnValue

Name of the added image.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [ImageFilterType](../../imagefiltertype/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(System::SharedPtr\<System::IO::Stream\>, int32_t) method


Adds entity to the end of the collection, so entity can be accessed by the last index.

```cpp
void Aspose::Pdf::XImageCollection::Add(System::SharedPtr<System::IO::Stream> image, int32_t quality)
```


| Parameter | Type | Description |
| --- | --- | --- |
| image | System::SharedPtr\<System::IO::Stream\> | Stream containing image data (in JPEG format). |
| quality | int32_t | JPEG quality. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
