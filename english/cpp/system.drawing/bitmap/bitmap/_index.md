---
title: System::Drawing::Bitmap::Bitmap constructor
linktitle: Bitmap
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Bitmap::Bitmap constructor. Constructs a new Bitmap object from the specified existing image in C++.'
type: docs
weight: 100
url: /cpp/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor


Constructs a new [Bitmap](../) object from the specified existing image.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


| Parameter | Type | Description |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | The existing image to create the bitmap image from |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor


Constructs a new [Bitmap](../) object from the specified existing image, scaled to the specified size.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


| Parameter | Type | Description |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | The existing image to create the bitmap image from |
| size | const Size\& | The size of the new image |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Size](../../size/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor


Constructs a new [Bitmap](../) object from the specified existing image with width and height scaled to the specified values.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


| Parameter | Type | Description |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | The existing image to create the bitmap image from |
| width | int | Width of the new image |
| height | int | Height of the new image |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor


Constructs a new [Bitmap](../) object from the specified stream.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<System::IO::Stream\>\& | A stream that contains image data |
| useIcm | bool | IGNORED |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&) constructor


Constructs a new [Bitmap](../) object from the specified file.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const String\& | A name of the file that contains image data |

## See Also

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&, bool) constructor


Constructs a new [Bitmap](../) object from the specified file.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const String\& | A name of the file that contains image data |
| useIcm | bool | IGNORED |

## See Also

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor


Constructs a new [Bitmap](../) object that represents a bitmap image with the specified width, height, pixel format and pixel data.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the image |
| height | int | The height of the image |
| format | Imaging::PixelFormat | The pixel format of the image |

## See Also

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
