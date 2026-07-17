---
title: Aspose::Pdf::Page::AddImage method
linktitle: AddImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Page::AddImage method. Adds image onto the page and locates it in the middle of specified rectangle saving image''s proportion in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/page/addimage/
---
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) method


Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr, bool autoAdjustRectangle=true)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | The stream of the image. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | The position of the image. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbox of the image. |
| autoAdjustRectangle | bool | Adjust image in center of the input rectangle. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Adds image on page and places it depend on image rectangle position.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, System::SharedPtr<Aspose::Pdf::Rectangle> imageRect, int32_t imageWidth, int32_t imageHeight, bool saveImageProportions, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | The stream of the image. |
| imageRect | System::SharedPtr\<Aspose::Pdf::Rectangle\> | The default position of the image on page. |
| imageWidth | int32_t | The width of the image. |
| imageHeight | int32_t | The height of the image. |
| saveImageProportions | bool | If the flag set to true than image placed in rectangle position; otherwise, the size of rectange is becoming equal to image size. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | The bbox of the image. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &hocr, const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hocr | const System::String\& | The hocr of the image. |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | The stream of the image. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | The position of the image. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | The bbox of the image. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &imagePath, const System::SharedPtr<Aspose::Pdf::Rectangle> &rectangle)
```


| Parameter | Type | Description |
| --- | --- | --- |
| imagePath | const System::String\& | The path to image. |
| rectangle | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | The position of the image. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
