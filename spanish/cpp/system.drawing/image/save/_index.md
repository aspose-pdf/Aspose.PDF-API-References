---
title: "System::Drawing::Image::Save method"
linktitle: "Guardar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Image::Save method. Guarda la imagen representada por el objeto actual en el flujo especificado usando el codificador y los parámetros del codificador especificados en C++."
type: docs
weight: 2200
url: /es/cpp/system.drawing/image/save/
---
## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Guarda la imagen representada por el objeto actual en el flujo especificado usando el codificador especificado y sus parámetros.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<System::IO::Stream\>\& | Un flujo para guardar la imagen |
| encoder | const Imaging::ImageCodecInfoPtr\& | El codificador a usar |
| encoder_params | const Imaging::EncoderParametersPtr\& | Los parámetros del codificador a usar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) method


Guarda la imagen representada por el objeto actual en el flujo especificado en el formato especificado.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const SharedPtr\<System::IO::Stream\>\& | Un flujo para guardar la imagen |
| formato | const Imaging::ImageFormatPtr\& | Un formato para guardar la imagen |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&) method


Guarda la imagen representada por el objeto actual en el archivo especificado en formato PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const String\& | El nombre del archivo donde guardar la imagen |

## Ver también

* Class [String](../../../system/string/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) method


Guarda la imagen representada por el objeto actual en el archivo especificado usando el codificador especificado y sus parámetros.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const String\& | El nombre del archivo donde guardar la imagen |
| encoder | const Imaging::ImageCodecInfoPtr\& | El codificador a usar |
| encoder_params | const Imaging::EncoderParametersPtr\& | Los parámetros del codificador a usar |

## Ver también

* Class [String](../../../system/string/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) method


Guarda la imagen representada por el objeto actual en el archivo especificado en el formato especificado.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | const String\& | El nombre del archivo donde guardar la imagen |
| formato | const Imaging::ImageFormatPtr\& | Un formato para guardar la imagen |

## Ver también

* Class [String](../../../system/string/)
* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
