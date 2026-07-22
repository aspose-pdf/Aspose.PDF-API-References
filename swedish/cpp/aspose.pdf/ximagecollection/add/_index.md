---
title: "Aspose::Pdf::XImageCollection::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XImageCollection::Add metod. Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf/ximagecollection/add/
---
## XImageCollection::Add(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) method


Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<Aspose::Pdf::BitmapInfo> &bitmapInfo)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmapInfo | const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\& | Objekt som innehåller en array av pixlar och bitmapinformation (Width, Height, PixelFormat). |

### ReturnValue

Namnet på den tillagda bilden.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BitmapInfo](../../bitmapinfo/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&, Aspose::Pdf::ImageFilterType) method


Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<Aspose::Pdf::BitmapInfo> &bitmapInfo, Aspose::Pdf::ImageFilterType filterType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmapInfo | const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\& | Objekt som innehåller en array av pixlar och bitmapinformation (Width, Height, PixelFormat). |
| filterType | Aspose::Pdf::ImageFilterType | Bildfiltertypen. |

### ReturnValue

Namnet på den tillagda bilden.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BitmapInfo](../../bitmapinfo/)
* Enum [ImageFilterType](../../imagefiltertype/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<System::IO::Stream\>\&) method


Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<System::IO::Stream> &image)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller bilddata (i JPEG-format). |

### ReturnValue

Namnet på den tillagda bilden.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::ImageFilterType) method


Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<System::IO::Stream> &image, Aspose::Pdf::ImageFilterType filterType)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller bilddata. |
| filterType | Aspose::Pdf::ImageFilterType | Bildfiltertypen. |

### ReturnValue

Namnet på den tillagda bilden.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [ImageFilterType](../../imagefiltertype/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) method


Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```cpp
void Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<System::IO::Stream> &image, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller bilddata (i JPEG-format). |
| kvalitet | int32_t | JPEG-kvalitet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
