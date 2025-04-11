---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.SideBySideComparisonOptions class. Represents an options class for comparing documents with sidebyside output
type: docs
weight: 3290
url: /it/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

Rappresenta una classe di opzioni per confrontare documenti con output affiancato.

```csharp
public class SideBySideComparisonOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Il costruttore predefinito. |

## Properties

| Name | Description |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Ottiene e imposta la proprietà che determina se i marcatori di cambiamento aggiuntivi vengono visualizzati. Se impostato, visualizza i marcatori di cambiamento che non sono sulla pagina corrente ma sono presenti su un'altra pagina. Se il cambiamento si trova tra le parole, il marcatore potrebbe non essere posizionato esattamente rispetto al carattere di spazio. Il valore predefinito è `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Ottiene e imposta l'area di confronto. Utilizzato per la prima pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme alle opzioni [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Ottiene e imposta l'area di confronto. Utilizzato per la seconda pagina o documento nel metodo di confronto. Questa opzione non può essere impostata insieme alle opzioni [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Ottiene e imposta una modalità di confronto. Il valore predefinito è !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Ottiene e imposta le aree escluse. Utilizzato per la prima pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a [`ExcludeTables`](./excludetables/). Questa opzione non può essere impostata insieme all'opzione [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Ottiene e imposta le aree escluse. Utilizzato per la seconda pagina o documento nel metodo di confronto. Questa opzione può essere impostata insieme a [`ExcludeTables`](./excludetables/). Questa opzione non può essere impostata insieme all'opzione [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Ottiene e imposta l'opzione che determina se le tabelle sono escluse dal confronto. Questa opzione non può essere impostata insieme a [`ComparisonArea1`](./comparisonarea1/) e [`ComparisonArea2`](./comparisonarea2/). Il valore predefinito è `false`. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)