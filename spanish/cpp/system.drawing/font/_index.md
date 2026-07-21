---
title: "Clase System::Drawing::Font"
linktitle: "Fuente"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Font. Representa un formato particular para texto, incluyendo el tipo de fuente, tamaño y estilo. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.drawing/font/
---
## Font class


Representa un formato particular para texto, incluyendo el tipo de fuente, tamaño y estilo. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Font : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() | Devuelve una copia de la fuente actual. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina si el objeto actual y el objeto especificado son idénticos. |
| [Font](./font/)(const SharedPtr\<Font\>\&, FontStyle) | Construye una nueva instancia de la clase [Font](./) que representa la fuente existente especificada con el estilo de fuente especificado. |
| [Font](./font/)(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) | Construye una nueva instancia de la clase [Font](./). |
| [Font](./font/)(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) | Construye una nueva instancia de la clase [Font](./). |
| [Font](./font/)(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) | Construye una nueva instancia de la clase [Font](./). |
| [Font](./font/)(const String\&, float, GraphicsUnit) | Construye una nueva instancia de la clase [Font](./). |
| static [FromLogFont](./fromlogfont/)(const SharedPtr\<Object\>\&) | NO IMPLEMENTADO. |
| [get_Bold](./get_bold/)() | Determina si la fuente representada por el objeto actual tiene aplicado el estilo negrita. |
| [get_FontFamily](./get_fontfamily/)() | Devuelve la familia tipográfica de la fuente representada por el objeto actual. |
| [get_FontStyle](./get_fontstyle/)() | Devuelve el estilo de la fuente representada por el objeto actual. |
| [get_GdiCharSet](./get_gdicharset/)() | Devuelve un valor que indica el conjunto de caracteres GDI usado por la fuente representada por el objeto actual. |
| [get_Height](./get_height/)() | Devuelve el interlineado de la fuente representada por el objeto actual en píxeles. |
| [get_Italic](./get_italic/)() | Determina si la fuente representada por el objeto actual tiene aplicado el estilo cursiva. |
| [get_Name](./get_name/)() | Devuelve el nombre de familia de la fuente representada por el objeto actual. |
| [get_OriginalFontName](./get_originalfontname/)() | Devuelve el nombre especificado originalmente de la fuente. |
| [get_Size](./get_size/)() | Devuelve el tamaño em de la fuente representada por el objeto actual medido en las unidades especificadas por la propiedad Unit. |
| [get_SizeInPoints](./get_sizeinpoints/)() | Devuelve el tamaño em de la fuente representada por el objeto actual en puntos. |
| [get_Strikeout](./get_strikeout/)() | Determina si la fuente representada por el objeto actual tiene aplicado el estilo tachado. |
| [get_Style](./get_style/)() | Devuelve el estilo de fuente de la fuente representada por el objeto actual. |
| [get_Underline](./get_underline/)() | Determina si la fuente representada por el objeto actual tiene aplicado el estilo subrayado. |
| [get_Unit](./get_unit/)() | Devuelve la unidad de medida de la fuente representada por el objeto actual. |
| [GetHeight](./getheight/)(const SharedPtr\<Graphics\>\&) | Devuelve el interlineado de la fuente representada por el objeto actual, en la unidad actual de un objeto [Graphics](../graphics/) especificado. |
| [GetHeight](./getheight/)(float) | Devuelve la altura de la fuente representada por el objeto actual cuando se dibuja en un dispositivo de pantalla con la resolución vertical especificada. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
