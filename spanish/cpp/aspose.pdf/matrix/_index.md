---
title: "Aspose::Pdf::Matrix clase"
linktitle: "Matrix"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Matrix clase. Clase que representa la matriz de transformación en C++."
type: docs
weight: 10900
url: /es/cpp/aspose.pdf/matrix/
---
## Matrix class


Clase que representa la matriz de transformación.

```cpp
class Matrix : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Matrix\>\&) | Añade la matriz a otra matriz. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Compara la matriz con otro objeto. |
| [get_A](./get_a/)() | Un miembro de la matriz de transformación. |
| [get_B](./get_b/)() | Miembro B de la matriz de transformación. |
| [get_C](./get_c/)() | Miembro C de la matriz de transformación. |
| [get_D](./get_d/)() | Miembro D de la matriz de transformación. |
| [get_Data](./get_data/)() const | Obtiene los datos de [Matrix](./) como una matriz. |
| [get_E](./get_e/)() | Miembro E de la matriz de transformación. |
| [get_Elements](./get_elements/)() | Elementos de la matriz. |
| [get_F](./get_f/)() | Miembro F de la matriz de transformación. |
| static [GetAngle](./getangle/)(Aspose::Pdf::Rotation) | Convierte la rotación en ángulo (grados) |
| [GetFlipMatrix](./getflipmatrix/)() | Obtiene la matriz de volteo. |
| [GetHashCode](./gethashcode/)() const override | Código hash para el objeto. |
| [Matrix](./matrix/)() | El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]. |
| [Matrix](./matrix/)(const System::ArrayPtr\<double\>\&) | El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F ]. |
| [Matrix](./matrix/)(const System::Details::ArrayView\<float\>\&) | El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F ]. |
| [Matrix](./matrix/)(const System::SharedPtr\<Matrix\>\&) | El constructor acepta una matriz para crear una copia. |
| [Matrix](./matrix/)(double, double, double, double, double, double) | Inicializa la matriz de transformación con los coeficientes especificados. |
| [Multiply](./multiply/)(const System::SharedPtr\<Matrix\>\&) | Multiplica la matriz por otra matriz. |
| [Reverse](./reverse/)() | Calcula la matriz inversa. |
| static [Rotation](./rotation/)(double) | Crea una matriz para el ángulo de rotación dado. |
| static [Rotation](./rotation/)(Aspose::Pdf::Rotation) | Crea una matriz para la rotación dada. |
| [Scale](./scale/)(double, double, double\&, double\&) | Escala x e y con la matriz usando la siguiente fórmula: x1 = A*x + C*y; y1 = B*x + D*y;. |
| static [Scale](./scale/)(double, double, const System::SharedPtr\<Matrix\>\&) | Aplica escalado a la matriz dada. |
| [set_A](./set_a/)(double) | Un miembro de la matriz de transformación. |
| [set_B](./set_b/)(double) | Miembro B de la matriz de transformación. |
| [set_C](./set_c/)(double) | Miembro C de la matriz de transformación. |
| [set_D](./set_d/)(double) | Miembro D de la matriz de transformación. |
| [set_E](./set_e/)(double) | Miembro E de la matriz de transformación. |
| [set_F](./set_f/)(double) | Miembro F de la matriz de transformación. |
| static [Skew](./skew/)(double, double) | Crea una matriz para el ángulo de rotación dado. |
| [ToString](./tostring/)() const override | Devuelve la representación textual de la matriz. |
| [Transform](./transform/)(const System::SharedPtr\<Point\>\&) | Transforma el punto usando esta matriz. |
| [Transform](./transform/)(double, double, double\&, double\&) | Transforma las coordenadas usando esta matriz. |
| [Transform](./transform/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Transforma el rectángulo. Si el ángulo no es 90 * N grados, se devuelve el rectángulo delimitador. |
| static [Translate](./translate/)(double, double, const System::SharedPtr\<Matrix\>\&) | Traslada una matriz por la cantidad especificada en la dirección x e y. |
| [UnScale](./unscale/)(double, double, double\&, double\&) | Desescala x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);. |
| [UnTransform](./untransform/)(double, double, double\&, double\&) | Transforma de vuelta x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
