---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.DifferenzaImmagini. Rappresenta la classe del risultato del confronto tra due pagine PDF.
type: docs
weight: 3230
url: /it/net/aspose.pdf.comparison/imagesdifference/
---
## Classe ImagesDifference

Rappresenta la classe risultato del confronto di due pagine PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Ottiene l'array delle differenze. Questo array è simile all'array dei dati dell'immagine originale ottenuto come risultato del metodo LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | L'altezza della differenza. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Ottiene l'immagine della prima pagina confrontata. L'immagine ha un formato pixel di 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Lo stride dei dati dell'immagine di differenza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Converte l'array delle differenze in un'immagine bitmap utilizzando i colori specificati. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Esegue eventuali operazioni di pulizia necessarie prima che l'oggetto venga distrutto. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Restituisce un nuovo bitmap che rappresenta l'immagine di destinazione applicando l'array delle differenze all'immagine sorgente. |

### Vedi Anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)