---
title: "System::Drawing::Drawing2D::Matrix class"
linktitle: "Matrix"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Drawing2D::Matrix class. Representa una matriz 3x3 que define operaciones de transformación. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.drawing.drawing2d/matrix/
---
## Matrix class


Representa una matriz 3x3 que define operaciones de transformación. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Matrix : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() const | Crea una copia del objeto actual. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [Equals](./equals/)(ptr) override | Comprueba si el objeto especificado es un [Matrix](./) y es idéntico a este objeto. |
| [get_Elements](./get_elements/)() const | Devuelve una matriz que contiene los elementos de la matriz en el siguiente orden: m11, m12, m21, m22, dx, dy. |
| [get_IsIdentity](./get_isidentity/)() const | Determina si la matriz representada por el objeto actual es una matriz identidad. |
| [get_IsInvertible](./get_isinvertible/)() const | Determina si la matriz representada por el objeto actual es invertible. |
| [get_OffsetX](./get_offsetx/)() const | Devuelve el valor de traslación X de la matriz representada por el objeto actual. |
| [get_OffsetY](./get_offsety/)() const | Devuelve el valor de traslación Y de la matriz representada por el objeto actual. |
| [Invert](./invert/)() | Invierte la matriz representada por el objeto actual. |
| [Matrix](./matrix/)() | Construye una nueva instancia de la clase [Matrix](./) que representa una matriz identidad. |
| [Matrix](./matrix/)(float, float, float, float, float, float) | Construye una nueva instancia de la clase [Matrix](./) y la inicializa con los valores especificados. |
| [Matrix](./matrix/)(const Rectangle\&, const ArrayPtr\<Point\>\&) | Construye una nueva instancia de la clase [Matrix](./) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Matrix](./matrix/)(const RectangleF\&, const ArrayPtr\<PointF\>\&) | Construye una nueva instancia de la clase [Matrix](./) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos. |
| [Multiply](./multiply/)(const SharedPtr\<Matrix\>\&) | Multiplica la matriz representada por el objeto actual por la matriz especificada. |
| [Multiply](./multiply/)(const SharedPtr\<Matrix\>\&, MatrixOrder) | Multiplica la matriz representada por el objeto actual por la matriz especificada. |
| [Reset](./reset/)() | Restablece la matriz representada por el objeto actual para que se convierta en una matriz identidad. |
| [Rotate](./rotate/)(float) | Rota la matriz representada por el objeto actual en sentido horario según el ángulo especificado. |
| [Rotate](./rotate/)(float, MatrixOrder) | Rota la matriz representada por el objeto actual en sentido horario alrededor del origen según el ángulo especificado. |
| [RotateAt](./rotateat/)(float, const PointF\&) | Rota la matriz representada por el objeto actual en sentido horario alrededor del punto especificado según el ángulo especificado. |
| [RotateAt](./rotateat/)(float, const PointF\&, MatrixOrder) | Rota la matriz representada por el objeto actual en sentido horario alrededor del punto especificado según el ángulo especificado. |
| [Scale](./scale/)(float, float) | Aplica el vector de escala especificado a la matriz representada por el objeto actual. |
| [Scale](./scale/)(float, float, MatrixOrder) | Aplica el vector de escala especificado a la matriz representada por el objeto actual. |
| [Shear](./shear/)(float, float) | Aplica el vector de cizallamiento especificado a la matriz representada por el objeto actual. |
| [Shear](./shear/)(float, float, MatrixOrder) | Aplica el vector de cizallamiento especificado a la matriz representada por el objeto actual. |
| [TransformPoints](./transformpoints/)(const ArrayPtr\<Point\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<Point\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| [TransformPoints](./transformpoints/)(const ArrayPtr\<PointF\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<PointF\>\&) | Aplica la transformación geométrica definida por la matriz representada por el objeto actual a los puntos especificados. |
| [TransformVectors](./transformvectors/)(const ArrayPtr\<Point\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<Point\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| [TransformVectors](./transformvectors/)(const ArrayPtr\<PointF\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<PointF\>\&) | Aplica solo los componentes de escala y rotación de la matriz representada por el objeto actual a los puntos especificados. |
| [Translate](./translate/)(float, float) | Aplica el vector de traslación especificado a la matriz representada por el objeto actual. |
| [Translate](./translate/)(float, float, MatrixOrder) | Aplica el vector de traslación especificado a la matriz representada por el objeto actual. |
| [VectorTransformPoints](./vectortransformpoints/)(const ArrayPtr\<Point\>\&) | Multiplica cada vector en una matriz por la matriz representada por el objeto actual. |
| [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<Point\>\&) | Multiplica cada vector en una matriz por la matriz representada por el objeto actual. |
| virtual [~Matrix](./~matrix/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
