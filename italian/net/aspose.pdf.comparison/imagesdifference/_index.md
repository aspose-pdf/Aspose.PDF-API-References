---
title: "Classe ImagesDifference"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Comparison.ImagesDifference. Rappresenta la classe risultato del confronto di due pagine PDF"
type: docs
weight: 3340
url: /it/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

Rappresenta la classe risultato del confronto di due pagine PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Ottiene l'array delle differenze. Questo array è simile all'array dei dati immagine originale ottenuto come risultato del metodo LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | L'altezza della differenza. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Ottiene l'immagine della prima pagina confrontata. L'immagine ha un formato pixel di 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Il passo dei dati immagine della differenza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Converte l'array delle differenze in un'immagine bitmap utilizzando i colori specificati. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Esegue le operazioni di pulizia necessarie prima che l'oggetto venga distrutto. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Restituisce un nuovo bitmap che rappresenta l'immagine di destinazione applicando l'array delle differenze all'immagine di origine. |

### Vedi anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


