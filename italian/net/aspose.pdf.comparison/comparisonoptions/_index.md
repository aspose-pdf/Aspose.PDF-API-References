---
title: "Classe ComparisonOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Comparison.ComparisonOptions. Rappresenta una classe di opzioni per il confronto di documenti PDF."
type: docs
weight: 3260
url: /it/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class

Rappresenta una classe di opzioni per il confronto di documenti PDF.

```csharp
public class ComparisonOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Ottiene e imposta l'ordine delle operazioni di modifica. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Ottieni e imposta le aree da escludere. Utilizzate per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a [`ExcludeTables`](./excludetables/). Questa opzione non può essere impostata insieme all'opzione [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Ottieni e imposta le aree da escludere. Utilizzate per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a [`ExcludeTables`](./excludetables/). Questa opzione non può essere impostata insieme all'opzione [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme all'opzione [`ExtractionArea`](./extractionarea/). Il valore predefinito è `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Ottieni e imposta l'area rettangolare in cui il testo delle pagine verrà confrontato. Questa opzione non può essere impostata insieme alle opzioni [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |

### Vedi anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


