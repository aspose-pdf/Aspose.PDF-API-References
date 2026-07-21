---
title: "System::Drawing::Imaging::BitmapData class"
linktitle: "BitmapData"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Imaging::BitmapData class. Representa un conjunto de atributos de una imagen bitmap. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.drawing.imaging/bitmapdata/
---
## BitmapData class


Representa un conjunto de atributos de una imagen bitmap. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class BitmapData : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Height](./get_height/)() const | Devuelve la altura de la imagen en píxeles. |
| [get_PixelFormat](./get_pixelformat/)() const | Devuelve el formato de píxel de la imagen bitmap. |
| [get_Scan0](./get_scan0/)() const | Devuelve la dirección del primer dato de píxel en el bitmap. |
| [get_Stride](./get_stride/)() const | Devuelve el ancho de paso de la imagen en bytes. |
| [get_Width](./get_width/)() const | Devuelve el ancho de la imagen en píxeles. |
| [set_Height](./set_height/)(int) | Establece la altura de la imagen en píxeles. |
| [set_PixelFormat](./set_pixelformat/)(PixelFormat) | Establece el formato de píxel de la imagen bitmap. |
| [set_Scan0](./set_scan0/)(IntPtr) | Establece la dirección del primer dato de píxel en el bitmap. |
| [set_Stride](./set_stride/)(int) | Establece el ancho de paso de la imagen en bytes. |
| [set_Width](./set_width/)(int) | Establece el ancho de la imagen en píxeles. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
