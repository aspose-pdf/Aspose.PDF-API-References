---
title: "System::Drawing::Imaging::ImageAttributes clase"
linktitle: "ImageAttributes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Imaging::ImageAttributes. Representa información sobre cómo se manipulan los colores de la imagen durante el renderizado. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.drawing.imaging/imageattributes/
---
## ImageAttributes class


Representa información sobre cómo se manipulan los colores de la imagen durante el renderizado. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ImageAttributes : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ClearBrushRemapTable](./clearbrushremaptable/)() | NO IMPLEMENTADO. |
| [ClearColorKey](./clearcolorkey/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [ClearColorMatrix](./clearcolormatrix/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [ClearGamma](./cleargamma/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [ClearNoOp](./clearnoop/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [ClearOutputChannel](./clearoutputchannel/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [ClearRemapTable](./clearremaptable/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [ClearThreshold](./clearthreshold/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [Clone](./clone/)() | Crea una copia del objeto actual. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [GetAdjustedPalette](./getadjustedpalette/)(const SharedPtr\<ColorPalette\>\&, ColorAdjustType) | NO IMPLEMENTADO. |
| [ImageAttributes](./imageattributes/)() | Constructor predeterminado. |
| [SetBrushRemapTable](./setbrushremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&) | NO IMPLEMENTADO. |
| [SetColorKey](./setcolorkey/)(Color, Color, ColorAdjustType) | NO IMPLEMENTADO. |
| [SetColorMatrices](./setcolormatrices/)(const SharedPtr\<ColorMatrix\>\&, const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | NO IMPLEMENTADO. |
| [SetColorMatrix](./setcolormatrix/)(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | Establece la matriz de ajuste de color. |
| [SetGamma](./setgamma/)(float, ColorAdjustType) | NO IMPLEMENTADO. |
| [SetNoOp](./setnoop/)(ColorAdjustType) | NO IMPLEMENTADO. |
| [SetOutputChannel](./setoutputchannel/)(ColorChannelFlag, ColorAdjustType) | NO IMPLEMENTADO. |
| [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const String\&, ColorAdjustType) | NO IMPLEMENTADO. |
| [SetRemapTable](./setremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&, ColorAdjustType) | NO IMPLEMENTADO. |
| [SetThreshold](./setthreshold/)(float, ColorAdjustType) | NO IMPLEMENTADO. |
| [SetWrapMode](./setwrapmode/)(Drawing2D::WrapMode, Color, bool) | Establece el modo de ajuste y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
