---
title: "System::Drawing::Bitmap class"
linktitle: "Bitmap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Bitmap. Representa una imagen bitmap GDI+. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.drawing/bitmap/
---
## Bitmap class


Representa una imagen bitmap GDI+. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Bitmap : public System::Drawing::Image
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BeginPixelProcessing](./beginpixelprocessing/)(bool) | Habilita el modo de procesamiento de píxeles. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&) | Construye un nuevo objeto [Bitmap](./) a partir de la imagen existente especificada. |
| [Bitmap](./bitmap/)(const SharedPtr\<System::IO::Stream\>\&, bool) | Construye un nuevo objeto [Bitmap](./) a partir del flujo especificado. |
| [Bitmap](./bitmap/)(const String\&) | Construye un nuevo objeto [Bitmap](./) a partir del archivo especificado. |
| [Bitmap](./bitmap/)(const String\&, bool) | Construye un nuevo objeto [Bitmap](./) a partir del archivo especificado. |
| [Bitmap](./bitmap/)(int, int, Imaging::PixelFormat) | Construye un nuevo objeto [Bitmap](./) que representa una imagen bitmap con el ancho, alto, formato de píxel y datos de píxel especificados. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, const Size\&) | Construye un nuevo objeto [Bitmap](./) a partir de la imagen existente especificada, escalada al tamaño especificado. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, int, int) | Construye un nuevo objeto [Bitmap](./) a partir de la imagen existente especificada con el ancho y alto escalados a los valores especificados. |
| [Clone](./clone/)() override | Crea una copia del objeto actual. |
| [Clone](./clone/)(Rectangle, Imaging::PixelFormat) | Crea un objeto [Bitmap](./) que representa una copia de una región de la imagen bitmap representada por el objeto actual. |
| [Clone](./clone/)(RectangleF, Imaging::PixelFormat) | Crea un objeto [Bitmap](./) que representa una copia de una región de la imagen bitmap representada por el objeto actual. |
| [ComputeHash](./computehash/)() | Calcula el valor hash SHA1. |
| static [ConvertToARGBImage](./converttoargbimage/)(const SharedPtr\<Bitmap\>\&) | Crea una copia de la imagen bitmap especificada con el formato de píxel cambiado a Format32bppArgb. |
| [EndPixelProcessing](./endpixelprocessing/)(bool) | Deshabilita el modo de procesamiento de píxeles. |
| [get_Height](./get_height/)() const override | Devuelve la altura de la imagen en píxeles. |
| [get_Palette](./get_palette/)() const override | Devuelve la paleta de colores utilizada por la imagen representada por el objeto actual. |
| [get_PixelFormat](./get_pixelformat/)() const override | Devuelve el formato de píxel de la imagen representada por el objeto actual. |
| [get_RawFormat](./get_rawformat/)() const override | Devuelve el formato de archivo de la imagen representada por el objeto actual. |
| [get_Width](./get_width/)() const override | Devuelve el ancho de la imagen en píxeles. |
| [GetHbitmap](./gethbitmap/)() | Crea un objeto bitmap GDI a partir del bitmap representado por el objeto actual. |
| [GetPixel](./getpixel/)(int, int) | Devuelve el color del píxel especificado. |
| [GetSkBitmap](./getskbitmap/)() const override | Devuelve un puntero sin procesar al objeto SkBitmap subyacente. |
| [IsMultiImage](./ismultiimage/)() const override | Devuelve si el formato original es una imagen múltiple. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) | Bloquea un [Bitmap](./) en la memoria del sistema. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) | Bloquea un [Bitmap](./) en la memoria del sistema. |
| [MakeTransparent](./maketransparent/)(Color) | Cambia el color de todos los píxeles con el color especificado a transparente. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(Bitmap, CODEPORTING_ARGS(const SharedPtr\<Image\>\&original, int width, int height), CODEPORTING_ARGS(original, width, height)) |  |
| [PremultipleColors](./premultiplecolors/)() | Pre-multiplica los colores de los píxeles de la imagen representada por el objeto actual. |
| [RotateFlip](./rotateflip/)(RotateFlipType) override | Rota la imagen a múltiplos de 90 grados y la voltea. |
| [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) override | Establece la paleta de colores utilizada por la imagen representada por el objeto actual. |
| [SetPixel](./setpixel/)(int, int, Color) | Establece el color del píxel especificado en la imagen bitmap representada por el objeto actual. |
| [SetResolution](./setresolution/)(float, float) | Establece la resolución de la imagen. |
| [UnlockBits](./unlockbits/)(const Imaging::BitmapDataPtr\&) | Desbloquea el bitmap especificado de la memoria del sistema. |
## Ver también

* Class [Image](../image/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
