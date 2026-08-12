---
title: "System::Drawing::Drawing2D::LinearGradientBrush class"
linktitle: "LinearGradientBrush"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Drawing2D::LinearGradientBrush class. Representa un pincel de degradado lineal. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 900
url: /es/cpp/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush class


Representa un pincel de degradado lineal. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Crea una copia del objeto actual. |
| [get_Blend](./get_blend/)() const | Devuelve una mezcla que especifica los factores y posiciones de los colores base para este pincel. |
| [get_GammaCorrection](./get_gammacorrection/)() const | Devuelve un valor que indica que la corrección gamma está habilitada para este pincel. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Devuelve un objeto [ColorBlend](../colorblend/) que define un degradado lineal multicolor. |
| [get_LinearColors](./get_linearcolors/)() const | Devuelve los colores inicial y final de este degradado. |
| [get_Rectangle](./get_rectangle/)() | Devuelve un rectángulo delimitador. |
| [get_Transform](./get_transform/)() const | Devuelve una copia de un objeto [Matrix](../matrix/) que especifica las transformaciones geométricas para el pincel representado por el objeto actual. |
| [get_WrapMode](./get_wrapmode/)() const | Devuelve el modo de ajuste. |
| [LinearGradientBrush](./lineargradientbrush/)(const PointF\&, const PointF\&, const Color\&, const Color\&) | Información RTTI. |
| [LinearGradientBrush](./lineargradientbrush/)(const Point\&, const Point\&, const Color\&, const Color\&) | Construye una nueva instancia de [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, LinearGradientMode) | Construye una nueva instancia de [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, LinearGradientMode) | Construye una nueva instancia de [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const RectangleF\&, const Color\&, const Color\&, float, bool) | Construye una nueva instancia de [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const Rectangle\&, const Color\&, const Color\&, float, bool) | Construye una nueva instancia de [LinearGradientBrush](./). |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplica la matriz de transformación del objeto actual por la matriz especificada. |
| [ResetTransform](./resettransform/)() | Restablece la matriz de transformación del objeto actual. |
| [RotateTransform](./rotatetransform/)(float, MatrixOrder) | Rota la matriz de transformación del objeto actual. |
| [ScaleTransform](./scaletransform/)(float, float, MatrixOrder) | Escala la matriz de transformación del objeto actual. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Establece una mezcla que especifica los factores y posiciones de los colores base para este pincel. |
| [set_GammaCorrection](./set_gammacorrection/)(bool) | Establece el estado de corrección gamma para este pincel. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Establece un objeto [ColorBlend](../colorblend/) que define un degradado lineal multicolor. |
| [set_LinearColors](./set_linearcolors/)(const ArrayPtr\<Color\>\&) | Establece los colores inicial y final de este degradado. |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Establece un objeto [Matrix](../matrix/) que especifica las transformaciones geométricas para el pincel representado por el objeto actual. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Establece el modo de ajuste. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | NO IMPLEMENTADO. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | NO IMPLEMENTADO. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Traslada la matriz de transformación del objeto actual. |
## Ver también

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
