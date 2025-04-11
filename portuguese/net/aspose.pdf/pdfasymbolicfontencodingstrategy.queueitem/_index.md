---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Especifica a sub-tabela de codificação. Cada sub-tabela de codificação tem uma combinação única de parâmetros PlatformID e PlatformSpecificId. A enumeração [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) e a propriedade [`CMapEncodingTable`](./cmapencodingtable/) foram implementadas para facilitar o conjunto de sub-tabelas de codificação necessárias.
type: docs
weight: 8340
url: /pt/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## Classe PdfASymbolicFontEncodingStrategy.QueueItem

Especifica a sub-tabela de codificação. Cada sub-tabela de codificação tem uma combinação única de parâmetros (PlatformID, PlatformSpecificId). A enumeração [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) e a propriedade [`CMapEncodingTable`](./cmapencodingtable/) foram implementadas para facilitar o conjunto de sub-tabelas de codificação necessárias.

```csharp
public class QueueItem
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Construtor, especifica a sub-tabela mac(1,0) por padrão |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Construtor |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Construtor |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Especifica a sub-tabela de codificação via enumeração [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Identificador da plataforma para a sub-tabela de codificação |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Identificador de codificação específico da plataforma para a sub-tabela de codificação |

### Veja Também

* classe [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)