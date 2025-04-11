---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin enum. The line join style shall specify the shape to be used at the corners of paths that are stroked
type: docs
weight: 7450
url: /it/net/aspose.pdf.operators/linejoin/
---
## Enumerazione LineJoin

Lo stile di giunzione della linea deve specificare la forma da utilizzare agli angoli dei percorsi che vengono tracciati.

```csharp
public enum LineJoin
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| MiterJoin | `0` | Giunzione a miter. I bordi esterni dei tratti per i due segmenti devono essere estesi fino a incontrarsi ad un angolo, come in una cornice. Se i segmenti si incontrano ad un angolo troppo acuto come definito dal parametro del limite di miter (vedi 8.4.3.5, "Limite di Miter"), deve essere utilizzata invece una giunzione a smusso. |
| RoundJoin | `1` | Giunzione arrotondata. Un arco di un cerchio con un diametro uguale alla larghezza della linea deve essere tracciato attorno al punto in cui i due segmenti si incontrano, collegando i bordi esterni dei tratti per i due segmenti. Questa figura a forma di fetta di torta deve essere riempita, producendo un angolo arrotondato. |
| BevelJoin | `2` | Giunzione a smusso. I due segmenti devono essere terminati con tappi a taglio (vedi 8.4.3.3, "Stile del Cappuccio della Linea") e il notch risultante oltre le estremità dei segmenti deve essere riempito con un triangolo. |

### Vedi Anche

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)