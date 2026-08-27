---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Lo stile di giunzione della linea deve specificare la forma da utilizzare agli angoli dei percorsi che vengono tracciati."
type: docs
weight: 370
url: /it/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

Lo stile di giunzione della linea deve specificare la forma da utilizzare agli angoli dei percorsi che vengono tracciati.

## Campi

| Campo | Descrizione |
| --- | --- |
| [BevelJoin](#BevelJoin) | Giunzione a smusso. I due segmenti devono essere terminati con cappucci a spalla (vedi 8.4.3.3, "Line Cap Style") e la rientranza risultante oltre le estremità dei segmenti deve essere riempita con un triangolo. |
| [MiterJoin](#MiterJoin) | Giunzione a spigolo. I bordi esterni dei tratti dei due segmenti devono essere estesi fino a incontrarsi ad un angolo, come in una cornice. Se i segmenti si incontrano con un angolo troppo acuto, come definito dal parametro limite di spigolo (vedi 8.4.3.5, "Miter Limit"), si utilizzerà invece una giunzione a smusso. |
| [RoundJoin](#RoundJoin) | Giunzione arrotondata. Un arco di un cerchio con diametro pari allo spessore della linea deve essere disegnato intorno al punto in cui i due segmenti si incontrano, collegando i bordi esterni dei tratti dei due segmenti. Questa figura a forma di fetta di torta deve essere riempita, producendo un angolo arrotondato. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

Giunzione a smusso. I due segmenti devono essere terminati con cappucci a spalla (vedi 8.4.3.3, "Line Cap Style") e la rientranza risultante oltre le estremità dei segmenti deve essere riempita con un triangolo.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

Giunzione a spigolo. I bordi esterni dei tratti dei due segmenti devono essere estesi fino a incontrarsi ad un angolo, come in una cornice. Se i segmenti si incontrano con un angolo troppo acuto, come definito dal parametro limite di spigolo (vedi 8.4.3.5, "Miter Limit"), si utilizzerà invece una giunzione a smusso.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

Giunzione arrotondata. Un arco di un cerchio con diametro pari allo spessore della linea deve essere disegnato intorno al punto in cui i due segmenti si incontrano, collegando i bordi esterni dei tratti dei due segmenti. Questa figura a forma di fetta di torta deve essere riempita, producendo un angolo arrotondato.
