---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.SideBySideComparisonOptions class. Representa uma classe de opções para comparar documentos com saída lado a lado
type: docs
weight: 3290
url: /pt/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

Representa uma classe de opções para comparar documentos com saída lado a lado.

```csharp
public class SideBySideComparisonOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | O construtor padrão. |

## Properties

| Name | Description |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Obtém e define a propriedade que determina se marcadores de mudança adicionais são exibidos. Se definido, exibe marcas de mudança que não estão na página atual, mas estão presentes em outra página. Se a mudança estiver entre palavras, a marca pode não estar posicionada exatamente em relação ao caractere de espaço em branco. O valor padrão é `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Obtém e define a área de comparação. Usado para a primeira página ou documento no método de comparação. Esta opção não pode ser definida junto com as opções [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Obtém e define a área de comparação. Usado para a segunda página ou documento no método de comparação. Esta opção não pode ser definida junto com as opções [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Obtém e define um modo de comparação. O valor padrão é !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Obtém e define as áreas a serem excluídas. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida junto com [`ExcludeTables`](./excludetables/). Esta opção não pode ser definida junto com a opção [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Obtém e define as áreas a serem excluídas. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida junto com [`ExcludeTables`](./excludetables/). Esta opção não pode ser definida junto com a opção [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida junto com [`ComparisonArea1`](./comparisonarea1/) e [`ComparisonArea2`](./comparisonarea2/). O valor padrão é `false`. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)