---
title: "Clase Aspose::Pdf::Image"
linktitle: "Imagen"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Image. Representa una imagen en C++."
type: docs
weight: 7900
url: /es/cpp/aspose.pdf/image/
---
## Image class


Representa una imagen.

```cpp
class Image : public Aspose::Pdf::BaseParagraph
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Clona la imagen. |
| [get_BitmapInfo](./get_bitmapinfo/)() const | Obtiene los bytes de la imagen sin comprimir. |
| [get_BitmapSize](./get_bitmapsize/)() | Obtiene el tamaño del mapa de bits de la imagen. |
| [get_File](./get_file/)() const | Obtiene el archivo de la imagen. |
| [get_FileType](./get_filetype/)() const | Obtiene el tipo de archivo de la imagen. |
| [get_FixHeight](./get_fixheight/)() const | Obtiene la altura de la imagen. |
| [get_FixWidth](./get_fixwidth/)() const | Obtiene el ancho de la imagen. |
| [get_ImageScale](./get_imagescale/)() const | Obtiene la escala de la imagen. |
| [get_ImageStream](./get_imagestream/)() const | Obtiene el flujo de la imagen. |
| [get_IsApplyResolution](./get_isapplyresolution/)() const | Obtiene un valor booleano que indica si la imagen usa resolución durante la generación. |
| [get_IsBlackWhite](./get_isblackwhite/)() const | Obtiene un valor booleano que indica si la imagen se fuerza a ser blanco y negro. Si se usa una imagen TIFF del subformato CCITT, esta propiedad debe establecerse en true. |
| [get_Title](./get_title/)() const | Obtiene un valor de cadena que indica el título de la imagen. |
| static [GetMimeType](./getmimetype/)(const System::SharedPtr\<System::Drawing::Image\>\&) | Devuelve el tipo mime de la imagen. |
| [Image](./image/)() |  |
| [set_BitmapInfo](./set_bitmapinfo/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) | Establece los bytes de la imagen sin comprimir. |
| [set_File](./set_file/)(const System::String\&) | Establece el archivo de imagen. |
| [set_FileType](./set_filetype/)(ImageFileType) | Establece el tipo de archivo de imagen. |
| [set_FixHeight](./set_fixheight/)(double) | Establece la altura de la imagen. |
| [set_FixWidth](./set_fixwidth/)(double) | Establece el ancho de la imagen. |
| [set_ImageScale](./set_imagescale/)(double) | Establece la escala de la imagen. |
| [set_ImageStream](./set_imagestream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de la imagen. |
| [set_IsApplyResolution](./set_isapplyresolution/)(bool) | Establece un valor booleano que indica si la imagen usa resolución durante la generación. |
| [set_IsBlackWhite](./set_isblackwhite/)(bool) | Establece un valor booleano que indica si la imagen se fuerza a ser blanco y negro. Si se usa una imagen TIFF del subformato CCITT, esta propiedad debe establecerse en verdadero. |
| [set_Title](./set_title/)(const System::SharedPtr\<Text::TextFragment\>\&) | Establece un valor de cadena que indica el título de la imagen. |
## Ver también

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
