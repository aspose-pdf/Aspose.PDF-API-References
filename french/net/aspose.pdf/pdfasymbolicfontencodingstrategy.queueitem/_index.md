---
title: "Classe PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Spécifie la sous-table d'encodage. Chaque sous-table d'encodage possède une combinaison unique de paramètres PlatformID PlatformSpecificId. L'énumération CMapEncodingTableType et la propriété CMapEncodingTable ont été implémentées pour faciliter la configuration de la sous-table d'encodage requise."
type: docs
weight: 8480
url: /fr/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem class

Spécifie la sous-table d'encodage. Chaque sous-table d'encodage possède une combinaison unique de paramètres (PlatformID, PlatformSpecificId). L'énumération [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) et la propriété [`CMapEncodingTable`](./cmapencodingtable/) ont été implémentées pour faciliter la configuration de la sous-table d'encodage requise.

```csharp
public class QueueItem
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Constructeur, spécifie la sous-table mac (1,0) par défaut |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Constructeur |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Constructeur |

## Propriétés

| Nom | Description |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Spécifie la sous-table d'encodage via l'énumération [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Identifiant de plateforme pour la sous-table d'encodage |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Identifiant d'encodage spécifique à la plateforme pour la sous-table d'encodage |

### Voir aussi

* class [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


