---
title: "Clase Aspose::Pdf::XImage"
linktitle: "XImage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::XImage. Clase que representa el X-Object de imagen en C++."
type: docs
weight: 19700
url: /es/cpp/aspose.pdf/ximage/
---
## XImage class


Clase que representa un X-Object de imagen.

```cpp
class XImage : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddStencilMask](./addstencilmask/)(const System::SharedPtr\<System::IO::Stream\>\&) | Añade una máscara de plantilla al [XImage](./). |
| static [DetectColorType](./detectcolortype/)(const System::SharedPtr\<System::Drawing::Bitmap\>\&) | Devuelve el tipo de color de la imagen. |
| [get_ContainsTransparency](./get_containstransparency/)() | Si la imagen contiene transparencia, devuelve true; de lo contrario, false. |
| [get_FilterType](./get_filtertype/)() | Obtiene el tipo de filtro de la imagen. |
| [get_Grayscaled](./get_grayscaled/)() | Obtiene la versión en escala de grises de la imagen. |
| [get_Height](./get_height/)() | Obtiene la altura de la imagen. |
| [get_ImageMask](./get_imagemask/)() | Obtiene una bandera que indica si la imagen debe tratarse como una máscara de imagen (ver 8.9.6, "Masked Images"). Si esta bandera es verdadera, el valor de BitsPerComponent debe ser 1 y Mask y [ColorSpace](../colorspace/) no deben especificarse; las áreas sin máscara deben pintarse usando el color actual de no trazo. Valor predeterminado: false. |
| [get_Metadata](./get_metadata/)() | [Metadata](../metadata/) de la imagen. |
| [get_Name](./get_name/)() | Obtiene el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede quedar incorrecto. Por favor, use el método [XImage.Rename](./rename/) en este caso. |
| [get_Width](./get_width/)() | Obtiene el ancho de la imagen. |
| [GetAlternativeText](./getalternativetext/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Devuelve una lista de cadenas con el [Text](../../aspose.pdf.text/) alternativo para un [XImage](./). |
| [GetColorType](./getcolortype/)() | Devuelve el tipo de color de la imagen. |
| [GetNameInCollection](./getnameincollection/)() | Devuelve el nombre de la imagen en su colección. |
| [GetRawImageData](./getrawimagedata/)() | Recupera los datos sin procesar de la imagen fuente. |
| [IsTheSameObject](./isthesameobject/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Devuelve true si ambas imágenes hacen referencia al mismo objeto. |
| [Rename](./rename/)(const System::String\&) | Renombra la imagen y reemplaza todas las referencias a la imagen con el nuevo nombre. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Guarda los datos de la imagen en el flujo como una imagen JPEG. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Guarda la imagen en el flujo con el formato solicitado. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Guarda los datos de la imagen en el flujo como una imagen JPEG con la resolución especificada. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Guarda la imagen en el flujo con el formato solicitado y la resolución especificada. |
| [set_Name](./set_name/)(const System::String\&) | Establece el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede quedar incorrecto. Por favor, use el método [XImage.Rename](./rename/) en este caso. |
| [ToStream](./tostream/)() | Devuelve el flujo de imagen original. |
| [TrySetAlternativeText](./trysetalternativetext/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Establece el texto alternativo para un [XImage](./) en la página. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
