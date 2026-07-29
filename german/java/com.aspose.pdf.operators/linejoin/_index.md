---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Der Linienstil für Verbindungen muss die Form angeben, die an den Ecken von Pfaden, die konturiert werden, verwendet wird."
type: docs
weight: 370
url: /de/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

Der Linienstil für Verbindungen muss die Form angeben, die an den Ecken von Pfaden, die konturiert werden, verwendet wird.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [BevelJoin](#BevelJoin) | Fasenverbindung. Die beiden Segmente sollen mit Butt-Kappen abgeschlossen werden (siehe 8.4.3.3, "Line Cap Style") und die daraus resultierende Kerbe jenseits der Enden der Segmente soll mit einem Dreieck gefüllt werden. |
| [MiterJoin](#MiterJoin) | Gehrungsverbindung. Die äußeren Kanten der Striche für die beiden Segmente sollen verlängert werden, bis sie sich in einem Winkel treffen, wie bei einem Bilderrahmen. Treffen die Segmente in einem zu spitzen Winkel, wie durch den Gehrungsgrenzwert-Parameter definiert (siehe 8.4.3.5, "Miter Limit"), wird stattdessen eine Fasenverbindung verwendet. |
| [RoundJoin](#RoundJoin) | Runde Verbindung. Ein Kreisbogen mit einem Durchmesser, der der Linienbreite entspricht, soll um den Punkt gezeichnet werden, an dem die beiden Segmente zusammentreffen, und die äußeren Kanten der Striche für die beiden Segmente verbinden. Diese sektorenförmige Figur soll ausgefüllt werden und eine abgerundete Ecke erzeugen. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

Fasenverbindung. Die beiden Segmente sollen mit Butt-Kappen abgeschlossen werden (siehe 8.4.3.3, "Line Cap Style") und die daraus resultierende Kerbe jenseits der Enden der Segmente soll mit einem Dreieck gefüllt werden.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

Gehrungsverbindung. Die äußeren Kanten der Striche für die beiden Segmente sollen verlängert werden, bis sie sich in einem Winkel treffen, wie bei einem Bilderrahmen. Treffen die Segmente in einem zu spitzen Winkel, wie durch den Gehrungsgrenzwert-Parameter definiert (siehe 8.4.3.5, "Miter Limit"), wird stattdessen eine Fasenverbindung verwendet.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

Runde Verbindung. Ein Kreisbogen mit einem Durchmesser, der der Linienbreite entspricht, soll um den Punkt gezeichnet werden, an dem die beiden Segmente zusammentreffen, und die äußeren Kanten der Striche für die beiden Segmente verbinden. Diese sektorenförmige Figur soll ausgefüllt werden und eine abgerundete Ecke erzeugen.
