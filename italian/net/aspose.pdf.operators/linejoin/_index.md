---
title: "Enum LineJoin"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.Operators.LineJoin. Lo stile di unione delle linee deve specificare la forma da utilizzare negli angoli dei percorsi tracciati"
type: docs
weight: 7590
url: /it/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

Lo stile di giunzione della linea deve specificare la forma da utilizzare agli angoli dei percorsi che vengono tracciati.

```csharp
public enum LineJoin
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| MiterJoin | `0` | Giunzione a spigolo. I bordi esterni delle linee per i due segmenti devono essere estesi finché non si incontrano a un angolo, come in una cornice. Se i segmenti si incontrano a un angolo troppo acuto, come definito dal parametro limite di spigolo (vedi 8.4.3.5, "Miter Limit"), si deve utilizzare invece una giunzione a smusso. |
| RoundJoin | `1` | Giunzione arrotondata. Un arco di un cerchio con diametro pari allo spessore della linea deve essere disegnato attorno al punto in cui i due segmenti si incontrano, collegando i bordi esterni dei tratti dei due segmenti. Questa figura a forma di fetta di torta deve essere riempita, producendo un angolo arrotondato. |
| BevelJoin | `2` | Giunzione smussata. I due segmenti devono essere terminati con cappucci a sbieco (vedi 8.4.3.3, "Line Cap Style") e la rientranza risultante oltre le estremità dei segmenti deve essere riempita con un triangolo. |

### Vedi anche

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


