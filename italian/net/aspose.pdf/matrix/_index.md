---
title: Matrix
second_title: Aspose.PDF per .NET API Reference
description: La classe rappresenta la matrice di trasformazione.
type: docs
weight: 4740
url: /it/net/aspose.pdf/matrix/
---
## Matrix class

La classe rappresenta la matrice di trasformazione.

```csharp
public sealed class Matrix
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Matrix](matrix#constructor)() | Il costruttore crea la matrice standard da 1 a 1: [ ABCDEF ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix#constructor_3)(double[]) | Il costruttore accetta una matrice con la seguente rappresentazione di matrice: [ ABCDEF ] |
| [Matrix](matrix#constructor_4)(float[]) | Il costruttore accetta una matrice con la seguente rappresentazione di matrice: [ ABCDEF ] |
| [Matrix](matrix#constructor_1)(Matrix) | Costruttore accetta una matrice per creare una copia |
| [Matrix](matrix#constructor_2)(double, double, double, double, double, double) | Inizializza la matrice di trasformazione con i coefficienti specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [A](../../aspose.pdf/matrix/a) { get; set; } | Un membro della matrice di trasformazione. |
| [B](../../aspose.pdf/matrix/b) { get; set; } | Membro B della matrice di trasformazione. |
| [C](../../aspose.pdf/matrix/c) { get; set; } | Membro C della matrice di trasformazione. |
| [D](../../aspose.pdf/matrix/d) { get; set; } | Membro D della matrice di trasformazione. |
| [Data](../../aspose.pdf/matrix/data) { get; } | Ottiene i dati di Matrix come array. |
| [E](../../aspose.pdf/matrix/e) { get; set; } | E membro della matrice di trasformazione. |
| [Elements](../../aspose.pdf/matrix/elements) { get; } | Elementi della matrice. |
| [F](../../aspose.pdf/matrix/f) { get; set; } | Membro F della matrice di trasformazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation_1)(double) | Crea la matrice per un dato angolo di rotazione. |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation)(Rotation) | Crea la matrice per una data rotazione. |
| static [Skew](../../aspose.pdf/matrix/skew)(double, double) | Crea la matrice per un dato angolo di rotazione. |
| [Add](../../aspose.pdf/matrix/add)(Matrix) | Aggiunge la matrice ad un'altra matrice. |
| override [Equals](../../aspose.pdf/matrix/equals)(object) | Confronta la matrice con un altro oggetto. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode)() | Codice hash per l'oggetto. |
| [Multiply](../../aspose.pdf/matrix/multiply)(Matrix) | Moltiplica la matrice per un'altra matrice. |
| [Reverse](../../aspose.pdf/matrix/reverse)() | Calcola la matrice inversa. |
| override [ToString](../../aspose.pdf/matrix/tostring)() | Restituisce la rappresentazione testuale della matrice. |
| [Transform](../../aspose.pdf/matrix/transform#transform)(Point) | Trasforma il punto usando questa matrice. |
| [Transform](../../aspose.pdf/matrix/transform#transform_1)(Rectangle) | Trasforma il rettangolo. Se l'angolo non è 90 * N gradi, viene restituito il rettangolo di delimitazione. |
| static [GetAngle](../../aspose.pdf/matrix/getangle)(Rotation) | Trasforma la rotazione in angolo (gradi) |

### Guarda anche

* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->