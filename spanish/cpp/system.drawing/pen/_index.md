---
title: "System::Drawing::Pen class"
linktitle: "Pen"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Pen. Representa propiedades como color, ancho, etc., de las líneas y curvas que se dibujan. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1500
url: /es/cpp/system.drawing/pen/
---
## Pen class


Representa propiedades como color, ancho, etc., de las líneas y curvas que se dibujan. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Pen : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() | Devuelve una copia del objeto actual. |
| [Dispose](./dispose/)() | Libera todos los recursos operativos adquiridos por el objeto actual. |
| [get_Alignment](./get_alignment/)() const | Devuelve un valor que indica la alineación del objeto [Pen](./) actual. |
| [get_Brush](./get_brush/)() | Devuelve el objeto [Brush](../brush/) de este Pen. |
| [get_Color](./get_color/)() const | Devuelve el color de este Pen. |
| [get_CompoundArray](./get_compoundarray/)() const | Devuelve una matriz de valores que especifica un lápiz compuesto. |
| [get_DashCap](./get_dashcap/)() const | Devuelve un valor que indica la tapa utilizada en ambos extremos de una línea discontinua. |
| [get_DashOffset](./get_dashoffset/)() const | Devuelve la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [get_DashPattern](./get_dashpattern/)() const | Devuelve una matriz que indica el patrón de guiones personalizado en una línea discontinua. |
| [get_DashStyle](./get_dashstyle/)() const | Devuelve un valor que indica el estilo de guiones del objeto [Pen](./) actual. |
| [get_EndCap](./get_endcap/)() const | Devuelve un valor que indica la tapa final de línea del objeto [Pen](./) actual. |
| [get_LineJoin](./get_linejoin/)() const | Devuelve un valor que indica cómo se unen las líneas dibujadas por este objeto [Pen](./). |
| [get_MiterLimit](./get_miterlimit/)() const | Devuelve el límite del grosor de la unión en una esquina biselada. |
| [get_PenType](./get_pentype/)() const | NO IMPLEMENTADO. |
| [get_StartCap](./get_startcap/)() const | Devuelve un valor que indica la tapa inicial de línea del objeto [Pen](./) actual. |
| [get_Transform](./get_transform/)() | Devuelve una copia de un objeto Matrix que especifica las transformaciones geométricas para el lápiz representado por el objeto actual. |
| [get_Width](./get_width/)() const | Devuelve el ancho del objeto [Pen](./) actual. |
| [MultiplyTransform](./multiplytransform/)(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) | Multiplica la matriz de transformación del objeto actual por la matriz especificada. |
| [Pen](./pen/)(const Color\&) | Construye un nuevo objeto [Pen](./) que representa el color especificado. |
| [Pen](./pen/)(const Color\&, float) | Construye un nuevo objeto [Pen](./) que representa el color y ancho especificados. |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&) | Construye un nuevo objeto [Pen](./) y lo inicializa con el objeto [Brush](../brush/) especificado. |
| [Pen](./pen/)(const SharedPtr\<Brush\>\&, float) | Construye un nuevo objeto [Pen](./) y lo inicializa con el objeto [Brush](../brush/) especificado. |
| [ResetTransform](./resettransform/)() | Restablece la matriz de transformación del objeto actual para que se convierta en una matriz identidad. |
| [RotateTransform](./rotatetransform/)(float, Drawing2D::MatrixOrder) | Rota la transformación geométrica local por el ángulo especificado en el orden especificado. |
| [ScaleTransform](./scaletransform/)(float, float, Drawing2D::MatrixOrder) | Escala la transformación geométrica local por los factores especificados en el orden especificado. |
| [set_Alignment](./set_alignment/)(Drawing2D::PenAlignment) | Establece la alineación del objeto [Pen](./) actual. |
| [set_Brush](./set_brush/)(const SharedPtr\<Brush\>\&) | Establece el objeto [Brush](../brush/) de este lápiz. |
| [set_Color](./set_color/)(const Color\&) | Establece el color de este lápiz. |
| [set_CompoundArray](./set_compoundarray/)(const System::ArrayPtr\<float\>\&) | Establece una matriz de valores que especifica un lápiz compuesto. |
| [set_CustomEndCap](./set_customendcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Establece la tapa final de línea personalizada. |
| [set_CustomStartCap](./set_customstartcap/)(const SharedPtr\<Drawing2D::CustomLineCap\>\&) | Establece la tapa inicial de línea personalizada. |
| [set_DashCap](./set_dashcap/)(Drawing2D::DashCap) | Establece un valor que especifica la tapa utilizada en ambos extremos de una línea discontinua. |
| [set_DashOffset](./set_dashoffset/)(float) | Establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| [set_DashPattern](./set_dashpattern/)(const System::ArrayPtr\<float\>\&) | Establece una matriz que especifica el patrón de guiones personalizado en una línea discontinua. La matriz consta de números que especifican las longitudes de guiones y espacios alternados. |
| [set_DashStyle](./set_dashstyle/)(Drawing2D::DashStyle) | Establece un valor que especifica el estilo de guiones del objeto [Pen](./) actual. |
| [set_EndCap](./set_endcap/)(Drawing2D::LineCap) | Establece la tapa final de línea del objeto [Pen](./) actual. |
| [set_LineJoin](./set_linejoin/)(Drawing2D::LineJoin) | Establece un valor que especifica cómo se unen las líneas dibujadas por este objeto [Pen](./). |
| [set_MiterLimit](./set_miterlimit/)(float) | Establece el límite del grosor de la unión en una esquina biselada. |
| [set_StartCap](./set_startcap/)(Drawing2D::LineCap) | Establece el extremo inicial de línea del objeto [Pen](./) actual. |
| [set_Transform](./set_transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Establece un objeto Matrix que especifica las transformaciones geométricas para el pen representado por el objeto actual. |
| [set_Width](./set_width/)(float) | Establece el ancho del objeto [Pen](./) actual. |
| [SetLineCap](./setlinecap/)(Drawing2D::LineCap, Drawing2D::LineCap, Drawing2D::DashCap) | NO IMPLEMENTADO. |
| [TranslateTransform](./translatetransform/)(float, float, Drawing2D::MatrixOrder) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden especificado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
