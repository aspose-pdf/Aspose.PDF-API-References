---
title: System::Drawing::Image::Save method
linktitle: Save
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Image::Save method. Saves the image represented by the current object to the specified stream using the specified encoder and encoder parameters in C++.'
type: docs
weight: 2200
url: /cpp/system.drawing/image/save/
---
## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Saves the image represented by the current object to the specified stream using the specified encoder and encoder parameters.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<System::IO::Stream\>\& | A stream to save the image to |
| encoder | const Imaging::ImageCodecInfoPtr\& | The encoder to use |
| encoder_params | const Imaging::EncoderParametersPtr\& | The parameters of the encoder to used |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) method


Saves the image represented by the current object to the specified stream in the specified format.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<System::IO::Stream\>\& | A stream to save the image to |
| format | const Imaging::ImageFormatPtr\& | A format to save the image in |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&) method


Saves the image represented by the current object to the specified file in PNG format.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const String\& | The name of the file to save the image to |

## See Also

* Class [String](../../../system/string/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Saves the image represented by the current object to the specified file using the specified encoder and encoder parameters.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const String\& | The name of the file to save the image to |
| encoder | const Imaging::ImageCodecInfoPtr\& | The encoder to use |
| encoder_params | const Imaging::EncoderParametersPtr\& | The parameters of the encoder to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) method


Saves the image represented by the current object to the specified file in the specified format.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | const String\& | The name of the file to save the image to |
| format | const Imaging::ImageFormatPtr\& | A format to save the image in |

## See Also

* Class [String](../../../system/string/)
* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
