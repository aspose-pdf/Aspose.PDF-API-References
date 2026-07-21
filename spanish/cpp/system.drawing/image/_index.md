---
title: "System::Drawing::Image clase"
linktitle: "Imagen"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Image clase. Una clase base para las clases System::Drawing::Bitmap y System::Drawing::Metafile que proporciona funcionalidad básica. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.drawing/image/
---
## Image class


Una clase base para [System::Drawing::Bitmap](../bitmap/) y las clases System::Drawing::Metafile que proporciona funcionalidad básica. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Image : public virtual System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Clone](./clone/)() | Crea una copia del objeto actual. |
| [Dispose](./dispose/)() override | Libera todos los recursos adquiridos por el objeto actual. |
| static [FromFile](./fromfile/)(const String\&, bool) | Crea un objeto [Image](./) a partir del archivo especificado. |
| static [FromHbitmap](./fromhbitmap/)(IntPtr) | Construye un objeto [Bitmap](../bitmap/) a partir del bitmap GDI especificado. |
| static [FromStream](./fromstream/)(const SharedPtr\<System::IO::Stream\>\&, bool, bool) | Crea un objeto [Image](./) a partir del flujo especificado. |
| virtual [get_Flags](./get_flags/)() const | Devuelve una combinación bit a bit de los valores del enumerado ImageFlags que representa los atributos de la imagen. |
| [get_FrameDimensionsList](./get_framedimensionslist/)() const | Devuelve una matriz de GUID que representan las dimensiones de los fotogramas dentro de la imagen representada por el objeto actual. |
| virtual [get_Height](./get_height/)() const | Devuelve la altura de la imagen en píxeles. |
| [get_HorizontalResolution](./get_horizontalresolution/)() const | Devuelve la resolución horizontal de la imagen representada por el objeto actual en píxeles por pulgada. |
| virtual [get_Palette](./get_palette/)() const | Devuelve la paleta de colores utilizada por la imagen representada por el objeto actual. |
| virtual [get_PixelFormat](./get_pixelformat/)() const | Devuelve el formato de píxel de la imagen representada por el objeto actual. |
| virtual [get_PropertyIdList](./get_propertyidlist/)() const | Obtiene los ID de los elementos de propiedad almacenados en esta imagen. |
| virtual [get_PropertyItems](./get_propertyitems/)() const | Obtiene todos los elementos de propiedad (fragmentos de metadatos) almacenados en esta imagen. |
| virtual [get_RawFormat](./get_rawformat/)() const | Devuelve el formato de archivo de la imagen representada por el objeto actual. |
| [get_Size](./get_size/)() const | Devuelve un objeto [Size](../size/) que representa el ancho y la altura de la imagen en píxeles. |
| virtual [get_Tag](./get_tag/)() const | Obtiene un objeto que proporciona datos adicionales sobre la imagen. |
| [get_VerticalResolution](./get_verticalresolution/)() const | Devuelve la resolución vertical de la imagen representada por el objeto actual en píxeles por pulgada. |
| virtual [get_Width](./get_width/)() const | Devuelve el ancho de la imagen en píxeles. |
| [GetBounds](./getbounds/)(GraphicsUnit\&) | Devuelve los límites de la imagen en las unidades de medida especificadas. |
| [GetFrameCount](./getframecount/)(const Imaging::FrameDimensionPtr\&) | Devuelve el número de fotogramas de la dimensión de fotograma especificada. |
| static [GetPixelFormatSize](./getpixelformatsize/)(Imaging::PixelFormat) | Devuelve el número de bits utilizados para representar la profundidad de color en el formato de píxel especificado. |
| virtual [GetSkBitmap](./getskbitmap/)() const | Devuelve un objeto SkBitmap subyacente. |
| [GetThumbnailImage](./getthumbnailimage/)(int, int, Image::GetThumbnailImageAbort, IntPtr) | Obtiene una miniatura para este objeto [System::Drawing::Image](./). |
| static [IsAlphaPixelFormat](./isalphapixelformat/)(Imaging::PixelFormat) | Determina si el formato de píxel especificado contiene información alfa. |
| virtual [IsMultiImage](./ismultiimage/)() const | Devuelve si el formato original es una imagen múltiple. |
| virtual [RotateFlip](./rotateflip/)(RotateFlipType) | Rota la imagen a múltiplos de 90 grados y la voltea. |
| [Save](./save/)(const String\&) | Guarda la imagen representada por el objeto actual en el archivo especificado en formato PNG. |
| [Save](./save/)(const String\&, const Imaging::ImageFormatPtr\&) | Guarda la imagen representada por el objeto actual en el archivo especificado en el formato especificado. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) | Guarda la imagen representada por el objeto actual en el flujo especificado en el formato especificado. |
| [Save](./save/)(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Guarda la imagen representada por el objeto actual en el archivo especificado usando el codificador especificado y sus parámetros. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Guarda la imagen representada por el objeto actual en el flujo especificado usando el codificador especificado y sus parámetros. |
| [SaveAdd](./saveadd/)(const Imaging::EncoderParametersPtr\&) | Añade un fotograma al archivo o flujo especificado en una llamada previa al método [Save()](./save/). |
| [SaveAdd](./saveadd/)(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) | Añade un fotograma al archivo o flujo especificado en una llamada previa al método [Save()](./save/). |
| [SelectActiveFrame](./selectactiveframe/)(const Imaging::FrameDimensionPtr\&, int) | Selecciona el fotograma especificado. |
| virtual [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) | Establece la paleta de colores utilizada por la imagen representada por el objeto actual. |
| virtual [set_Tag](./set_tag/)(const System::SharedPtr\<System::Object\>) | Establece un objeto que proporciona datos adicionales sobre la imagen. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | Una devolución de llamada para cancelar la ejecución de GetThumbnailImage. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
