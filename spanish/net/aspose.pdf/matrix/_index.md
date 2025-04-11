---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Matrix. La clase representa una matriz de transformación
type: docs
weight: 6920
url: /es/net/aspose.pdf/matrix/
---
## Clase Matrix

La clase representa una matriz de transformación.

```csharp
public sealed class Matrix
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Matrix](matrix/#constructor)() | El constructor crea una matriz estándar de 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | El constructor acepta una matriz con la siguiente representación de array: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | El constructor acepta una matriz con la siguiente representación de array: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | El constructor acepta una matriz para crear una copia |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Inicializa la matriz de transformación con los coeficientes especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Un miembro de la matriz de transformación. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Miembro B de la matriz de transformación. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Miembro C de la matriz de transformación. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Miembro D de la matriz de transformación. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Obtiene los datos de la matriz como array. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Miembro E de la matriz de transformación. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Elementos de la matriz. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Miembro F de la matriz de transformación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Crea una matriz para el ángulo de rotación dado. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Crea una matriz para la rotación dada. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Aplica escalado a la matriz dada. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Crea una matriz para el ángulo de rotación dado. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Traduce una matriz por la cantidad especificada en la dirección x e y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Suma la matriz a otra matriz. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Compara la matriz con otro objeto. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Obtiene la matriz de inversión. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Código hash para el objeto. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Multiplica la matriz por otra matriz. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Calcula la matriz inversa. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Escala x e y con la matriz usando la siguiente fórmula: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Devuelve la representación textual de la matriz. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Transforma el punto usando esta matriz. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Transforma el rectángulo. Si el ángulo no es 90 * N grados, entonces se devuelve el rectángulo delimitador. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Transforma las coordenadas usando esta matriz. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Escala de nuevo x1 e y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Transforma de nuevo x1 e y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Traduce la rotación en ángulo (grados) |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)