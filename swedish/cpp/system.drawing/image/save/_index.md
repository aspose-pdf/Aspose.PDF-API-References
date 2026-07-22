---
title: "System::Drawing::Image::Save metod"
linktitle: "Spara"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Image::Save metod. Sparar bilden som representeras av det aktuella objektet till den angivna strömmen med den angivna kodaren och kodarparametrarna i C++."
type: docs
weight: 2200
url: /sv/cpp/system.drawing/image/save/
---
## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Sparar bilden som representeras av det aktuella objektet till den angivna strömmen med den angivna kodaren och kodarparametrarna.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<System::IO::Stream\>\& | En ström att spara bilden till |
| encoder | const Imaging::ImageCodecInfoPtr\& | Kodaren att använda |
| encoder_params | const Imaging::EncoderParametersPtr\& | Parametrarna för kodaren som används |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) method


Sparar bilden som representeras av det aktuella objektet till den angivna strömmen i det angivna formatet.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<System::IO::Stream\>\& | En ström att spara bilden till |
| format | const Imaging::ImageFormatPtr\& | Ett format att spara bilden i |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&) method


Sparar bilden som representeras av det aktuella objektet till den angivna filen i PNG-format.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const String\& | Namnet på filen att spara bilden till |

## Se även

* Class [String](../../../system/string/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Sparar bilden som representeras av det aktuella objektet till den angivna filen med den angivna kodaren och kodarparametrarna.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const String\& | Namnet på filen att spara bilden till |
| encoder | const Imaging::ImageCodecInfoPtr\& | Kodaren att använda |
| encoder_params | const Imaging::EncoderParametersPtr\& | Parametrarna för den kodare som ska användas |

## Se även

* Class [String](../../../system/string/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) method


Sparar bilden som representeras av det aktuella objektet till den angivna filen i det angivna formatet.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const String\& | Namnet på filen att spara bilden till |
| format | const Imaging::ImageFormatPtr\& | Ett format att spara bilden i |

## Se även

* Class [String](../../../system/string/)
* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
