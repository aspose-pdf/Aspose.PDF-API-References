---
title: "Classe SideBySideComparisonOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Comparison.SideBySideComparisonOptions. Rappresenta una classe di opzioni per confrontare documenti con output sidebyside."
type: docs
weight: 3400
url: /it/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

Rappresenta una classe di opzioni per confrontare documenti con output affiancato.

```csharp
public class SideBySideComparisonOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Ottieni e imposta la proprietà che determina se i marcatori di modifica aggiuntivi sono visualizzati. Se impostata, visualizza i segni di modifica che non sono nella pagina corrente ma sono presenti in un'altra pagina. Se la modifica si trova tra parole, il segno potrebbe non essere posizionato esattamente rispetto al carattere di spazio. Il valore predefinito è `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Ottieni e imposta l'area di confronto. Utilizzata per la prima pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Ottieni e imposta l'area di confronto. Utilizzata per la seconda pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme a [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Ottiene e imposta una modalità di confronto. Il valore predefinito è !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Ottieni e imposta le aree da escludere. Utilizzate per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a [`ExcludeTables`](./excludetables/). Questa opzione non può essere impostata insieme all'opzione [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Ottieni e imposta le aree da escludere. Utilizzate per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a [`ExcludeTables`](./excludetables/). Questa opzione non può essere impostata insieme all'opzione [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Ottieni e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a [`ComparisonArea1`](./comparisonarea1/) e [`ComparisonArea2`](./comparisonarea2/). Il valore predefinito è `false`. |

### Vedi anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


