---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.ComparisonOptions. Representa uma classe de opções de comparação de documentos PDF
type: docs
weight: 3150
url: /pt/net/aspose.pdf.comparison/comparisonoptions/
---
## Classe ComparisonOptions

Representa uma classe de opções de comparação de documentos PDF.

```csharp
public class ComparisonOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Obtém e define a ordem das operações de edição. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Obtém e define as áreas a serem excluídas. Usado para a primeira página ou documento no método de comparação. Esta opção pode ser definida junto com [`ExcludeTables`](./excludetables/). Esta opção não pode ser definida junto com a opção [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Obtém e define as áreas a serem excluídas. Usado para a segunda página ou documento no método de comparação. Esta opção pode ser definida junto com [`ExcludeTables`](./excludetables/). Esta opção não pode ser definida junto com a opção [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Obtém e define a opção que determina se as tabelas são excluídas da comparação. Esta opção não pode ser definida junto com a opção [`ExtractionArea`](./extractionarea/). O valor padrão é `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Obtém e define a área retangular na qual o texto das páginas será comparado. Esta opção não pode ser definida junto com as opções [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) e [`ExcludeAreas2`](./excludeareas2/). |

### Veja Também

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)