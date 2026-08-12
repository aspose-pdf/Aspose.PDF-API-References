---
title: "System::Drawing::Imaging::ImageCodecInfo clase"
linktitle: "ImageCodecInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Imaging::ImageCodecInfo clase. Proporciona información sobre un códec de imagen. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.drawing.imaging/imagecodecinfo/
---
## ImageCodecInfo class


Proporciona información sobre un códec de imagen. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ImageCodecInfo : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_FormatID](./get_formatid/)() const | Devuelve un GUID asociado con el formato del códec representado por el objeto actual. |
| [get_MimeType](./get_mimetype/)() | Devuelve el tipo Multipurpose Internet Mail Extensions (MIME) del códec representado por el objeto actual. |
| static [GetImageDecoders](./getimagedecoders/)() | Devuelve una matriz de objetos [ImageCodecInfo](./) que representan decodificadores de imagen compatibles. |
| static [GetImageEncoders](./getimageencoders/)() | Devuelve una matriz de objetos [ImageCodecInfo](./) que representan codificadores de imagen compatibles. |
| [set_FormatID](./set_formatid/)(const Guid\&) | Establece un GUID asociado con el formato del códec representado por el objeto actual. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
