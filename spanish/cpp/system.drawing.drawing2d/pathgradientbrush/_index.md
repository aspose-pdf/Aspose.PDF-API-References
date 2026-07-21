---
title: "System::Drawing::Drawing2D::PathGradientBrush clase"
linktitle: "PathGradientBrush"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Drawing2D::PathGradientBrush clase. Representa una brocha que rellena el interior de un objeto GraphicsPath con un degradado. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1200
url: /es/cpp/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush class


Representa una brocha que rellena el interior de un objeto [GraphicsPath](../graphicspath/) con un degradado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Crea una copia del objeto actual. |
| [get_Blend](./get_blend/)() const | NO IMPLEMENTADO. |
| [get_CenterColor](./get_centercolor/)() const | Devuelve un color que está en el centro de la ruta rellenada por el objeto actual. |
| [get_CenterPoint](./get_centerpoint/)() const | Obtiene el punto central del degradado. |
| [get_FocusScales](./get_focusscales/)() const | Obtiene el punto focal para la caída del degradado. |
| [get_InterpolationColors](./get_interpolationcolors/)() const | Devuelve un valor que define un degradado lineal multicolor. |
| [get_Rectangle](./get_rectangle/)() | NO IMPLEMENTADO. |
| [get_SurroundColors](./get_surroundcolors/)() const | Devuelve los colores que corresponden a los puntos en la ruta que rellena este [PathGradientBrush](./). |
| [get_Transform](./get_transform/)() const | Devuelve una copia de un objeto [Matrix](../matrix/) que especifica las transformaciones geométricas para el pincel representado por el objeto actual. |
| [get_WrapMode](./get_wrapmode/)() const | Devuelve el modo de ajuste. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplica la matriz de transformación del objeto actual por la matriz especificada. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<PointF\>\&, WrapMode) | Información RTTI. |
| [PathGradientBrush](./pathgradientbrush/)(const ArrayPtr\<Point\>\&, WrapMode) | Construye una nueva instancia de la clase [PathGradientBrush](./). |
| [PathGradientBrush](./pathgradientbrush/)(const SharedPtr\<GraphicsPath\>\&) | Construye una nueva instancia de la clase [PathGradientBrush](./). |
| [ResetTransform](./resettransform/)() | Restablece la matriz de transformación del objeto actual para que se convierta en una matriz identidad. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Rota la transformación geométrica local por el ángulo especificado en el orden especificado. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Escala la transformación geométrica local por los factores especificados en el orden especificado. |
| [set_Blend](./set_blend/)(const SharedPtr\<Blend\>\&) | Establece una mezcla que especifica los factores y posiciones de los colores base para este pincel. |
| [set_CenterColor](./set_centercolor/)(Color) | Establece un color que está en el centro de la ruta rellenada por el objeto actual. |
| [set_CenterPoint](./set_centerpoint/)(const PointF\&) | Establece el punto central del degradado. |
| [set_FocusScales](./set_focusscales/)(const PointF\&) | Establece el punto focal para la caída del degradado. |
| [set_InterpolationColors](./set_interpolationcolors/)(const SharedPtr\<ColorBlend\>\&) | Establece un valor que define un degradado lineal multicolor. |
| [set_SurroundColors](./set_surroundcolors/)(const ArrayPtr\<Color\>\&) | Establece los colores que corresponden a los puntos en la ruta que rellena este [PathGradientBrush](./). |
| [set_Transform](./set_transform/)(const SharedPtr\<Matrix\>\&) | Establece un objeto [Matrix](../matrix/) que especifica las transformaciones geométricas para el pincel representado por el objeto actual. |
| [set_WrapMode](./set_wrapmode/)(WrapMode) | Establece el modo de ajuste. |
| [SetBlendTriangularShape](./setblendtriangularshape/)(float, float) | NO IMPLEMENTADO. |
| [SetSigmaBellShape](./setsigmabellshape/)(float, float) | NO IMPLEMENTADO. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
## Ver también

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
