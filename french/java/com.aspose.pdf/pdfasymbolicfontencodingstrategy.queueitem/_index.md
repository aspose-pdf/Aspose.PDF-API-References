---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie la sous-table d’encodage. Chaque sous-table d’encodage possède une combinaison unique de paramètres (PlatformID, PlatformSpecificID). Énumération {@code CMapEncodingTableType} et propriété."
type: docs
weight: 3700
url: /fr/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Spécifie la sous-table d'encodage. Chaque sous-table d'encodage a une combinaison unique de paramètres (PlatformID, PlatformSpecificID). L'énumération {@code CMapEncodingTableType} et la propriété {@code CMapEncodingTable} ont été implémentées pour faciliter la définition de la sous-table d'encodage requise.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [QueueItem](#QueueItem--) | Constructeur, spécifie la sous-table mac(1,0) par défaut |
| [QueueItem](#QueueItem-int-int-) | Constructeur |
| [QueueItem](#QueueItem-short-) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Spécifie la sous-table d’encodage via l’énumération {@code CMapEncodingTableType} |
| [getPlatformId](#getPlatformId--) | Identifiant de plateforme pour la sous-table d’encodage |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Identifiant d’encodage spécifique à la plateforme pour la sous-table d’encodage |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Spécifie la sous-table d’encodage via l’énumération {@code CMapEncodingTableType} |
| [setPlatformId](#setPlatformId-int-) | Identifiant de plateforme pour la sous-table d’encodage |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Identifiant d’encodage spécifique à la plateforme pour la sous-table d’encodage |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Constructeur, spécifie la sous-table mac(1,0) par défaut

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Constructeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| platformID |  | Identifiant de plateforme pour la sous-table d’encodage |
| platformSpecificID |  | Identifiant d’encodage spécifique à la plateforme pour la sous-table d’encodage |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Constructeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmapTable |  | sous-table d’encodage |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Spécifie la sous-table d’encodage via l’énumération {@code CMapEncodingTableType}

**Returns:**
sous-table d’encodage

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Identifiant de plateforme pour la sous-table d’encodage

**Returns:**
valeur int

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Identifiant d’encodage spécifique à la plateforme pour la sous-table d’encodage

**Returns:**
valeur int

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Spécifie la sous-table d’encodage via l’énumération {@code CMapEncodingTableType}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | sous-table d’encodage |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Identifiant de plateforme pour la sous-table d’encodage

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Identifiant d’encodage spécifique à la plateforme pour la sous-table d’encodage

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
