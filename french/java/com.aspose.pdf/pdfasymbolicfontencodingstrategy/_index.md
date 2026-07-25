---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe décrit les règles pouvant être utilisées pour ajuster le processus de copie des données d'encodage dans les cas où une police symbolique TrueType possède plusieurs encodages. Certains documents PDF après."
type: docs
weight: 3690
url: /fr/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Cette classe décrit les règles qui peuvent être utilisées pour ajuster le processus de copie des données d'encodage dans les cas où une police symbolique TrueType possède plus d'un encodage. Certains documents PDF après conversion au format PDF/A peuvent générer une erreur "More than one encoding in symbolic TrueType font's cmap". Quelle est la raison de cette erreur ? Toutes les polices symboliques TrueType ont une table spéciale "cmap" dans leurs données internes. Cette table associe les codes de caractères aux indices de glyphes. Et cette table peut contenir différentes sous‑tables d'encodage qui décrivent les encodages utilisés. Voir des informations avancées sur les tables cmap à https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Habituellement, la table cmap contient plusieurs sous‑tables d'encodage, mais la norme PDF/A exige qu'il ne reste qu'une seule sous‑table d'encodage pour cette police dans le document PDF/A ou qu'il y ait une sous‑table d'encodage (3,0) parmi les sous‑tables de cette police. Et la question clé ici – quelles données doivent être prises à partir des autres sous‑tables pour être copiées dans la table d'encodage de destination (3,0) ? La majorité des polices ont des tables cmap « bien formées » où chaque sous‑table d'encodage est entièrement cohérente avec une autre sous‑table. Mais certaines polices ont des tables cmap avec des collisions – où, par exemple, une sous‑table possède l'indice de glyphe 100 pour le caractère unicode 100, tandis qu'une autre sous‑table possède l'indice de glyphe 200 pour le même unicode 100. Pour résoudre ces problèmes, une stratégie spéciale est nécessaire. Par défaut, la stratégie suivante est utilisée : la sous‑table mac (1,0) est recherchée. Si cette table est trouvée, seules ces données sont utilisées pour remplir la table de destination (3,0). Si la sous‑table mac n'est pas trouvée, alors toutes les sous‑tables sauf (3,0) sont parcourues et utilisées pour copier les données dans la sous‑table de destination (3,0). De plus, le mappage pour chaque unicode (unicode, indice de glyphe) est copié dans la table de destination uniquement si la table de destination ne possède pas cet unicode à ce moment‑là. Ainsi, par exemple, si la première sous‑table a l'indice de glyphe 100 pour l'unicode 100, et que la sous‑table suivante a l'indice de glyphe 200 pour le même unicode 100, seules les données de la première sous‑table (unicode=100, indice de glyphe = 100) seront copiées. Ainsi chaque sous‑table précédente a la priorité sur la suivante. Les propriétés de cette classe { PdfASymbolicFontEncodingStrategy} aident à ajuster le comportement par défaut. Si la propriété {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) de type { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} est définie, alors la sous‑table pertinente sera utilisée en priorité par rapport à la sous‑table mac (1,0). La valeur 'MacTable' de l'énumération {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} n'a aucun sens dans ce cas, car elle pointe sur la même sous‑table mac (1,0) qui sera utilisée par défaut. La propriété {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) supprime toutes les priorités pour toute sous‑table. Si cette propriété est définie, alors seules les sous‑tables de la file d'attente déclarée seront utilisées dans l'ordre spécifié. Si les sous‑tables spécifiées ne sont pas trouvées, alors l'itération par défaut de toutes les sous‑tables et la stratégie de copie décrite ci‑dessus seront utilisées. L'objet { PdfASymbolicFontEncodingStrategy.QueueItem} spécifie la sous‑table d'encodage utilisée. Cette sous‑table peut être définie via une combinaison de membres (PlatformID, PlatformSpecificId) ou via l'énumération { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Dans le cas où la police n'a pas de sous‑table (3,0), une autre sous‑table sera utilisée pour maintenir la compatibilité PDF/A. Le choix de la sous‑table à utiliser est fait selon les mêmes règles décrites précédemment, de sorte que les propriétés {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) et {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) sont utilisées pour déterminer la sous‑table résultante, et si la police ne possède pas la ou les sous‑tables demandées, alors toute sous‑table existante sera utilisée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Constructeur. Définit la sous-table par défaut (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Constructeur. Définit la sous-table par défaut (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | Spécifie la file d'attente des sous-tables d'encodage à traiter. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | Spécifie la sous-table qui sera utilisée en priorité par rapport à la sous-table mac (1,0). La valeur 'MacTable' de l'énumération {@code QueueItem.CMapEncodingTableType} n'a aucun sens dans ce cas. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | Spécifie la file d'attente des sous-tables d'encodage à traiter. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | Spécifie la sous-table qui sera utilisée en priorité par rapport à la sous-table mac (1,0). La valeur 'MacTable' de l'énumération {@code QueueItem.CMapEncodingTableType} n'a aucun sens dans ce cas. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Constructeur. Définit la sous-table par défaut (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Constructeur. Définit la sous-table par défaut (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Constructeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| preferredEncodingTable |  | sous-table d'encodage qui sera utilisée en priorité par rapport à la sous-table mac (1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

Spécifie la file d'attente des sous-tables d'encodage à traiter.

**Returns:**
File d'attente de QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

Spécifie la sous-table qui sera utilisée en priorité par rapport à la sous-table mac (1,0). La valeur 'MacTable' de l'énumération {@code QueueItem.CMapEncodingTableType} n'a aucun sens dans ce cas.

**Returns:**
Élément CMapEncodingTableType @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
Spécifie la file d'attente des sous-tables d'encodage à traiter.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

Spécifie la sous-table qui sera utilisée en priorité par rapport à la sous-table mac (1,0). La valeur 'MacTable' de l'énumération {@code QueueItem.CMapEncodingTableType} n'a aucun sens dans ce cas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Sous-table d'encodage preferredEncodingTable qui sera utilisée en priorité par rapport à la sous-table mac(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
