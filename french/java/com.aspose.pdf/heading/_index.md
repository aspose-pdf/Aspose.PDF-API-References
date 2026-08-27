---
title: "En-tête"
linktitle: "En-tête"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'en-tête."
type: docs
weight: 1890
url: /fr/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Représente l'en-tête.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Heading](#Heading--) | À usage interne uniquement |
| [Heading](#Heading-int-) | Initialise une nouvelle instance de la classe Cell. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clone l'en-tête avec tous les segments. |
| [deepClone](#deepClone--) | Clone l'en-tête. |
| [getDestinationPage](#getDestinationPage--) | Obtient la page de destination. |
| [getLevel](#getLevel--) | Obtient le niveau. |
| [getStartNumber](#getStartNumber--) | Obtient le numéro de départ de l'en-tête. |
| [getStyle](#getStyle--) | Obtient ou définit le style. |
| [getTocPage](#getTocPage--) | Obtient la page qui contient cet en-tête. |
| [getTop](#getTop--) | Obtient le Y supérieur de ces en-têtes (pour usage interne). |
| [getUserLabel](#getUserLabel--) | Obtient ou définit l'étiquette utilisateur. |
| [isAutoSequence](#isAutoSequence--) | Obtient si l'en-tête doit être numéroté automatiquement. |
| [isInList](#isInList--) | Obtient si l'en-tête doit être dans la liste de la table des matières. |
| [setAutoSequence](#setAutoSequence-boolean-) | définit si l'en-tête doit être numéroté automatiquement. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | définit la page de destination. |
| [setInList](#setInList-boolean-) | définit si l'en-tête doit être dans la liste de la table des matières. |
| [setLevel](#setLevel-int-) | définit le niveau. |
| [setStartNumber](#setStartNumber-int-) | Obtient le numéro de départ du titre. Valeur : le startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | définit ou définit le style. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Définit la page qui contient ce titre. |
| [setTop](#setTop-double-) | définit le Y supérieur de ces titres (pour usage interne). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Obtient ou définit l'étiquette utilisateur. |

### Heading {#Heading--}
```
public Heading()
```

À usage interne uniquement

### Heading {#Heading-int-}
```
public Heading(int level)
```

Initialise une nouvelle instance de la classe Cell.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| level |  | Le niveau des titres. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clone l'en-tête avec tous les segments.

**Returns:**
L'objet cloné

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone l'en-tête.

**Returns:**
L'objet cloné

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Obtient la page de destination.

**Returns:**
La page de destination.

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtient le niveau.

**Returns:**
Le niveau du titre.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Obtient le numéro de départ de l'en-tête.

**Returns:**
Valeur : le startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Obtient ou définit le style.

**Returns:**
Le style du titre.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Obtient la page qui contient cet en-tête.

**Returns:**
La page.

### getTop {#getTop--}
```
public double getTop()
```

Obtient le Y supérieur de ces en-têtes (pour usage interne).

**Returns:**
La valeur Y supérieure

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Obtient ou définit l'étiquette utilisateur.

**Returns:**
Objet TextSegment

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Obtient si l'en-tête doit être numéroté automatiquement.

**Returns:**
Le IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Obtient si l'en-tête doit être dans la liste de la table des matières.

**Returns:**
Le IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

définit si l'en-tête doit être numéroté automatiquement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Le IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
définit la page de destination.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

définit si l'en-tête doit être dans la liste de la table des matières.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Le IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

définit le niveau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Le niveau du titre. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Obtient le numéro de départ du titre. Valeur : le startNumber.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Le startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
définit ou définit le style.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Définit la page qui contient ce titre.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

définit le Y supérieur de ces titres (pour usage interne).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | La valeur Y supérieure |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Obtient ou définit l'étiquette utilisateur.
