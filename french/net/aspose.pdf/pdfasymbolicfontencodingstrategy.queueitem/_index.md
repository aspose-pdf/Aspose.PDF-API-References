---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Spécifie la sous-table d'encodage. Chaque sous-table d'encodage a une combinaison unique de paramètres PlatformID PlatformSpecificId. L'énumération CMapEncodingTableType et la propriété CMapEncodingTable ont été mises en œuvre pour faciliter l'ensemble de la sous-table d'encodage nécessaire.
type: docs
weight: 8340
url: /fr/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## Classe PdfASymbolicFontEncodingStrategy.QueueItem

Spécifie la sous-table d'encodage. Chaque sous-table d'encodage a une combinaison unique de paramètres (PlatformID, PlatformSpecificId). L'énumération [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) et la propriété [`CMapEncodingTable`](./cmapencodingtable/) ont été mises en œuvre pour faciliter l'ensemble de la sous-table d'encodage nécessaire.

```csharp
public class QueueItem
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Constructeur, spécifie la sous-table mac(1,0) par défaut |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Constructeur |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Constructeur |

## Propriétés

| Nom | Description |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Spécifie la sous-table d'encodage via l'énumération [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Identifiant de la plateforme pour la sous-table d'encodage |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Identifiant d'encodage spécifique à la plateforme pour la sous-table d'encodage |

### Voir aussi

* classe [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)