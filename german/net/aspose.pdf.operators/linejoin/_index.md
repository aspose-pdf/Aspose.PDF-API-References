---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin Enum. Der Linienverbindungsstil gibt die Form an, die an den Ecken der gestrichenen Pfade verwendet werden soll.
type: docs
weight: 7450
url: /de/net/aspose.pdf.operators/linejoin/
---
## LineJoin Aufzählung

Der Linienverbindungsstil gibt die Form an, die an den Ecken der gestrichenen Pfade verwendet werden soll.

```csharp
public enum LineJoin
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| MiterJoin | `0` | Miter-Verbindung. Die äußeren Kanten der Striche für die beiden Segmente werden verlängert, bis sie sich in einem Winkel treffen, wie in einem Bilderrahmen. Wenn sich die Segmente in einem zu spitzen Winkel treffen, wie durch den Miter-Limit-Parameter definiert (siehe 8.4.3.5, "Miter-Limit"), wird stattdessen eine Fase verwendet. |
| RoundJoin | `1` | Runde Verbindung. Ein Bogen eines Kreises mit einem Durchmesser, der der Linienbreite entspricht, wird um den Punkt gezeichnet, an dem sich die beiden Segmente treffen, und verbindet die äußeren Kanten der Striche für die beiden Segmente. Diese kuchenstückförmige Figur wird ausgefüllt, wodurch eine abgerundete Ecke entsteht. |
| BevelJoin | `2` | Fasenverbindung. Die beiden Segmente werden mit geraden Kappen (siehe 8.4.3.3, "Linienkappenstil") abgeschlossen, und die resultierende Kerbe über die Enden der Segmente wird mit einem Dreieck gefüllt. |

### Siehe auch

* Namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* Assembly [Aspose.PDF](../../)