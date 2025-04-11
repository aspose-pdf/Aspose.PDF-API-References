---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Matrix. Classe representa a matriz de transformação
type: docs
weight: 6920
url: /pt/net/aspose.pdf/matrix/
---
## Classe Matrix

Classe representa a matriz de transformação.

```csharp
public sealed class Matrix
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Matrix](matrix/#constructor)() | O construtor cria uma matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | O construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | O construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | O construtor aceita uma matriz para criar uma cópia |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Inicializa a matriz de transformação com os coeficientes especificados. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Um membro da matriz de transformação. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Membro B da matriz de transformação. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Membro C da matriz de transformação. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Membro D da matriz de transformação. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Obtém os dados da matriz como array. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Membro E da matriz de transformação. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Elementos da matriz. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Membro F da matriz de transformação. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Cria uma matriz para o ângulo de rotação dado. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Cria uma matriz para a rotação dada. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Aplica escalonamento à matriz dada. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Cria uma matriz para o ângulo de rotação dado. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Translada uma matriz pela quantidade especificada na direção x e y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Adiciona a matriz a outra matriz. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Compara a matriz com outro objeto. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Obtém a matriz de inversão. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Código hash para o objeto. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Multiplica a matriz por outra matriz. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Calcula a matriz inversa. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Escala x e y com a matriz usando a seguinte fórmula: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Retorna a representação textual da matriz. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Transforma o ponto usando esta matriz. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Transforma o retângulo. Se o ângulo não for 90 * N graus, então o retângulo delimitador é retornado. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Transforma coordenadas usando esta matriz. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Reescala x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Transforma de volta x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Traduz a rotação em ângulo (graus) |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)