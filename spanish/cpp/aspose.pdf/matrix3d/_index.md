---
title: "Aspose::Pdf::Matrix3D clase"
linktitle: "Matrix3D"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Matrix3D clase. La clase representa una matriz de transformación en C++."
type: docs
weight: 11000
url: /es/cpp/aspose.pdf/matrix3d/
---
## Matrix3D class


Clase que representa la matriz de transformación.

```cpp
class Matrix3D : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Matrix3D\>\&) | Añade la matriz a otra matriz. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Compara la matriz con otro objeto. |
| [get_A](./get_a/)() | Un miembro de la matriz de transformación. |
| [get_B](./get_b/)() | Miembro B de la matriz de transformación. |
| [get_C](./get_c/)() | Miembro C de la matriz de transformación. |
| [get_D](./get_d/)() | Miembro D de la matriz de transformación. |
| [get_E](./get_e/)() | Miembro E de la matriz de transformación. |
| [get_F](./get_f/)() | Miembro F de la matriz de transformación. |
| [get_G](./get_g/)() | Miembro G de la matriz de transformación. |
| [get_H](./get_h/)() | Miembro H de la matriz de transformación. |
| [get_I](./get_i/)() | Miembro I de la matriz de transformación. |
| [get_Tx](./get_tx/)() | Miembro Tx de la matriz de transformación. |
| [get_Ty](./get_ty/)() | Miembro Ty de la matriz de transformación. |
| [get_Tz](./get_tz/)() | Miembro Tz de la matriz de transformación. |
| static [GetAngle](./getangle/)(Rotation) | Convierte la rotación en ángulo (grados). |
| [GetHashCode](./gethashcode/)() const override | Código hash para el objeto. |
| [Matrix3D](./matrix3d/)() | El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]. |
| [Matrix3D](./matrix3d/)(const System::ArrayPtr\<double\>\&) | El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F G H I Tx Ty Tz]. |
| [Matrix3D](./matrix3d/)(const System::SharedPtr\<Matrix3D\>\&) | El constructor acepta una matriz para crear una copia. |
| [Matrix3D](./matrix3d/)(double, double, double, double, double, double, double, double, double, double, double, double) | Inicializa la matriz de transformación con los coeficientes especificados. |
| [set_A](./set_a/)(double) | Un miembro de la matriz de transformación. |
| [set_B](./set_b/)(double) | Miembro B de la matriz de transformación. |
| [set_C](./set_c/)(double) | Miembro C de la matriz de transformación. |
| [set_D](./set_d/)(double) | Miembro D de la matriz de transformación. |
| [set_E](./set_e/)(double) | Miembro E de la matriz de transformación. |
| [set_F](./set_f/)(double) | Miembro F de la matriz de transformación. |
| [set_G](./set_g/)(double) | Miembro G de la matriz de transformación. |
| [set_H](./set_h/)(double) | Miembro H de la matriz de transformación. |
| [set_I](./set_i/)(double) | Miembro I de la matriz de transformación. |
| [set_Tx](./set_tx/)(double) | Miembro Tx de la matriz de transformación. |
| [set_Ty](./set_ty/)(double) | Miembro Ty de la matriz de transformación. |
| [set_Tz](./set_tz/)(double) | Miembro Tz de la matriz de transformación. |
| [ToString](./tostring/)() const override | Devuelve la representación textual de la matriz. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
