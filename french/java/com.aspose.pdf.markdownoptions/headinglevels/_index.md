---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de travailler avec les niveaux d'en-tête basés sur la taille de la police."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Représente une classe permettant de travailler avec les niveaux d'en-tête basés sur la taille de la police.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Crée une nouvelle instance de la classe HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Crée une nouvelle instance de la classe HeadingLevels. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Ajoute des niveaux de titre. |
| [estimateLevel](#estimateLevel-double-) | Estime le niveau d'en-tête possible. Si fontSize n'est pas trouvé dans la liste des niveaux, le niveau le plus proche de cette valeur de taille de police sera retourné. Si fontSize est en dehors des niveaux d'en-tête minimum et maximum spécifiés, la méthode renverra false. |
| [findLevel](#findLevel-double-int:A-) | Trouve le niveau correspondant à la taille de police. Recherche d'une correspondance exacte. |
| [getAllLevels](#getAllLevels--) | Obtient tous les niveaux de titre. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Crée une nouvelle instance de la classe HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Crée une nouvelle instance de la classe HeadingLevels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold |  | La valeur du seuil pour comparer les tailles de police. Dans le seuil, les niveaux d'en-tête sont identiques. La valeur par défaut du seuil est 0,01. |

### addLevels {#addLevels-java.lang.Iterable-}
Ajoute des niveaux de titre.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Estime le niveau d'en-tête possible. Si fontSize n'est pas trouvé dans la liste des niveaux, le niveau le plus proche de cette valeur de taille de police sera retourné. Si fontSize est en dehors des niveaux d'en-tête minimum et maximum spécifiés, la méthode renverra false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize |  | La taille de police. |

**Returns:**
Niveau de titre.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Trouve le niveau correspondant à la taille de police. Recherche d'une correspondance exacte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize |  | La taille de police. |
| level |  | Le niveau de titre correspondant à la taille de police donnée. |

**Returns:**
False si la fontSize n'est pas dans la plage spécifiée.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Obtient tous les niveaux de titre.

**Returns:**
IEnumerable of Double
