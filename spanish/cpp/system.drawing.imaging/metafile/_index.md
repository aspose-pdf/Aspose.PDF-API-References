---
title: "System::Drawing::Imaging::Metafile clase"
linktitle: "Metafile"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Imaging::Metafile clase. Representa un metafile gráfico. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.drawing.imaging/metafile/
---
## Metafile class


Representa un metafile gráfico. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Metafile : public System::Drawing::Image
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Devuelve una copia del objeto actual. |
| [get_Height](./get_height/)() const override | Devuelve las alturas de la imagen en píxeles. |
| [get_PixelFormat](./get_pixelformat/)() const override | Devuelve un valor que indica el formato de píxel. |
| [get_RawFormat](./get_rawformat/)() const override | Devuelve un valor que indica el formato de la imagen. |
| [get_Width](./get_width/)() const override | Devuelve el ancho de la imagen en píxeles. |
| [GetHenhmetafile](./gethenhmetafile/)() | NO IMPLEMENTADO. |
| [GetMetafileHeader](./getmetafileheader/)() | Devuelve un encabezado asociado con el objeto actual. |
| [Metafile](./metafile/)(const System::String\&) | NO IMPLEMENTADO. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&) | NO IMPLEMENTADO. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, EmfType) | NO IMPLEMENTADO. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr) | NO IMPLEMENTADO. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, Rectangle, MetafileFrameUnit, EmfType) | NO IMPLEMENTADO. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, RectangleF, MetafileFrameUnit, EmfType) | NO IMPLEMENTADO. |
| [Metafile](./metafile/)(IntPtr, EmfType) | NO IMPLEMENTADO. |
| [PlayRecord](./playrecord/)(EmfPlusRecordType, int32_t, int32_t, System::ByteArrayPtr) | NO IMPLEMENTADO. |
| virtual [~Metafile](./~metafile/)() | Destructor. |
## Ver también

* Class [Image](../../system.drawing/image/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
