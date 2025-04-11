---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix classe. La classe rappresenta matrice di trasformazione.
type: docs
weight: 6920
url: /it/net/aspose.pdf/matrix/
---
## Classe Matrix

La classe rappresenta una matrice di trasformazione.

```csharp
public sealed class Matrix
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Matrix](matrix/#constructor)() | Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Il costruttore accetta una matrice con la seguente rappresentazione dell'array: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Il costruttore accetta una matrice con la seguente rappresentazione dell'array: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Il costruttore accetta una matrice per creare una copia |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Inizializza la matrice di trasformazione con i coefficienti specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Un membro della matrice di trasformazione. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Membro B della matrice di trasformazione. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Membro C della matrice di trasformazione. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Membro D della matrice di trasformazione. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Ottiene i dati della matrice come array. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Membro E della matrice di trasformazione. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Elementi della matrice. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Membro F della matrice di trasformazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Crea una matrice per un dato angolo di rotazione. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Crea una matrice per una data rotazione. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Applica la scalatura alla matrice data. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Crea una matrice per un dato angolo di rotazione. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Trasla una matrice della quantità specificata nella direzione x e y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Aggiunge una matrice a un'altra matrice. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Confronta la matrice con un altro oggetto. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Ottiene la matrice di ribaltamento. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Codice hash per l'oggetto. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Moltiplica la matrice per un'altra matrice. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Calcola la matrice inversa. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Scala x e y con la matrice utilizzando la seguente formula: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Restituisce la rappresentazione testuale della matrice. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Trasforma il punto utilizzando questa matrice. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Trasforma il rettangolo. Se l'angolo non è di 90 * N gradi, viene restituito il rettangolo di delimitazione. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Trasforma le coordinate utilizzando questa matrice. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Scala indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice utilizzando la seguente formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Trasforma indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice utilizzando la seguente formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Traduce la rotazione in angolo (gradi) |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)