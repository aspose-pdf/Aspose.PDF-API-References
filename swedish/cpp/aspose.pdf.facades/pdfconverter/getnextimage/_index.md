---
title: "Aspose::Pdf::Facades::PdfConverter::GetNextImage metod"
linktitle: "GetNextImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfConverter::GetNextImage metod. Sparar bilden till en ström med standard bildformat - jpeg i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.pdf.facades/pdfconverter/getnextimage/
---
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&) method


Sparar bild till ström med standard bildformat - jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) method


Sparar bild till ström med given sidstorlek.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Bildens sidstorlek. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Sparar bild till ström med given sidstorlek.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Bildens sidstorlek. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Sparar bild till ström med given sidstorlek, bildformat och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Bildens sidstorlek. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Sparar bild till ström med givet bildformat.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) method


Sparar bild till ström med det angivna bildformatet, storlek och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, double imageWidth, double imageHeight, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| imageWidth | double | Bildens bredd, enheten är pixel. |
| imageHeight | double | Bildens höjd, enheten är pixel. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) method


Sparar bild till ström med det angivna bildformatet, storlek och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| imageWidth | int32_t | Bildens bredd, enheten är pixel. |
| imageHeight | int32_t | Bildens höjd, enheten är pixel. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) method


Sparar bild till ström med det angivna bildformatet, dimensioner och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| imageWidth | int32_t | Bildens bredd, enheten är pixel. |
| imageHeight | int32_t | Bildens höjd, enheten är pixel. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Sparar bild till ström med givet bildformat och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Strömmen för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&) method


Sparar bild till fil med standard bildformat - jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |

## Se även

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&) method


Sparar bild till fil med given sidstorlek och standard bildformat - jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Bildens sidstorlek. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Sparar bild till fil med given sidstorlek och bildformat.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Bildens sidstorlek. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Sparar bild till fil med given sidstorlek, bildformat och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Bildens sidstorlek. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Sparar bild till fil med det angivna bildformatet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) method


Sparar bild till fil med det angivna bildformatet, bildstorlek och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, double imageWidth, double imageHeight, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| imageWidth | double | Bildens bredd, enheten är pixlar. |
| imageHeight | double | Bildens höjd, enheten är pixlar.. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) method


Sparar bild till fil med det angivna bildformatet och dimensioner.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| imageWidth | int32_t | Bildens bredd, enheten är pixel. |
| imageHeight | int32_t | Bildens höjd, enheten är pixel. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) method


Sparar bild till fil med det angivna bildformatet, dimensioner och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| imageWidth | int32_t | Bildens bredd, enheten är pixel. |
| imageHeight | int32_t | Bildens höjd, enheten är pixel. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Sparar bild till fil med givet bildformat och kvalitet.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | const System::String\& | Filsökvägen och namn för att spara bilden. |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Bildens format. |
| kvalitet | int32_t | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
