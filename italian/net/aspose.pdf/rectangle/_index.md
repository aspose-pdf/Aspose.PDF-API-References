---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Rectangle. La classe rappresenta un rettangolo
type: docs
weight: 9750
url: /it/net/aspose.pdf/rectangle/
---
## Classe Rectangle

La classe rappresenta un rettangolo.

```csharp
public sealed class Rectangle : ICloneable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Costruttore di Rectangle. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Rettangolo vuoto |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Inizializza un rettangolo triviale, cioè un rettangolo con posizione e dimensioni nulle. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Altezza del rettangolo. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Controlla se il rettangolo è vuoto. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Controlla se il rettangolo è un punto, cioè LLX è uguale a URX e LLY è uguale a URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Controlla se il rettangolo è triviale, cioè ha dimensioni e posizione nulle. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Coordinata X dell'angolo inferiore sinistro. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Coordinata Y dell'angolo inferiore sinistro. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Coordinata X dell'angolo superiore destro. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Coordinata Y dell'angolo superiore destro. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Larghezza del rettangolo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Inizializza un nuovo rettangolo dall'istanza fornita di System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Inizializza un nuovo rettangolo dall'istanza fornita di System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Tenta di analizzare la stringa ed estrarre da essa i componenti del rettangolo llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Restituisce le coordinate del centro del rettangolo. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Clona l'oggetto Rectangle. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Determina se il punto fornito è all'interno del rettangolo. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Determina se il rettangolo contiene una linea rappresentata da due punti. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Determina se il punto fornito è contenuto all'interno del rettangolo. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Controlla se i rettangoli sono uguali, cioè hanno la stessa posizione e dimensioni. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Interseca due rettangoli. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Determina se questo rettangolo interseca un altro rettangolo. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Unisce i rettangoli. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Sposta il rettangolo dei delta specificati. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Controlla se i rettangoli sono quasi uguali, cioè hanno una posizione e dimensioni quasi identiche (fino al delta). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Ruota il rettangolo dell'angolo specificato. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Ruota il rettangolo dell'angolo specificato. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Converte il rettangolo in un array di punti ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Converte il rettangolo in un'istanza di System.Drawing.Rectangle. Le posizioni e le dimensioni in virgola mobile vengono troncate. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Ottiene la rappresentazione stringa del rettangolo. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)