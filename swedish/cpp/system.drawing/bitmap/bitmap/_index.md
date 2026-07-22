---
title: "System::Drawing::Bitmap::Bitmap konstruktor"
linktitle: "Bitmap"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Bitmap::Bitmap konstruktor. Skapar ett nytt Bitmap-objekt från den angivna befintliga bilden i C++."
type: docs
weight: 100
url: /sv/cpp/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor


Skapar ett nytt [Bitmap](../)-objekt från den angivna befintliga bilden.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | Den befintliga bilden att skapa bitmap-bilden från |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor


Skapar ett nytt [Bitmap](../)-objekt från den angivna befintliga bilden, skalad till den angivna storleken.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | Den befintliga bilden att skapa bitmap-bilden från |
| size | const Size\& | Storleken på den nya bilden |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Size](../../size/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor


Skapar ett nytt [Bitmap](../)-objekt från den angivna befintliga bilden med bredd och höjd skalade till de angivna värdena.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | const SharedPtr\<Image\>\& | Den befintliga bilden att skapa bitmap-bilden från |
| bredd | int | Bredd på den nya bilden |
| höjd | int | Höjd på den nya bilden |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor


Skapar ett nytt [Bitmap](../)-objekt från den angivna strömmen.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<System::IO::Stream\>\& | En ström som innehåller bilddata |
| useIcm | bool | IGNORED |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&) constructor


Skapar ett nytt [Bitmap](../)-objekt från den angivna filen.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const String\& | Ett namn på filen som innehåller bilddata |

## Se även

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&, bool) constructor


Skapar ett nytt [Bitmap](../)-objekt från den angivna filen.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const String\& | Ett namn på filen som innehåller bilddata |
| useIcm | bool | IGNORED |

## Se även

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor


Skapar ett nytt [Bitmap](../)-objekt som representerar en bitmap-bild med den angivna bredden, höjden, pixelformatet och pixeldata.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden på bilden |
| höjd | int | Höjden på bilden |
| format | Imaging::PixelFormat | Pixelformatet för bilden |

## Se även

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
