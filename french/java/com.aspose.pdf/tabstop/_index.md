---
title: "TabStop"
linktitle: "TabStop"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une position d'arrêt d'onglet personnalisée dans un paragraphe."
type: docs
weight: 4840
url: /fr/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Représente une position d'arrêt d'onglet personnalisée dans un paragraphe.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TabStop](#TabStop--) | Initialise une nouvelle instance de la classe {@code TabStop}. |
| [TabStop](#TabStop-float-) | Initialise une nouvelle instance de la classe {@code TabStop} avec la position spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Obtient ou définit une énumération {@code AlignmentType} qui indique le type d'alignement d'onglet. |
| [getLeaderType](#getLeaderType--) | Obtient ou définit une énumération {@code TabLeaderType} qui indique le type de leader d'onglet. |
| [getPosition](#getPosition--) | Obtient ou définit une valeur flottante qui indique la position du tab stop. |
| [isReadOnly](#isReadOnly--) | Obtient la valeur indiquant que cette instance {@code TabStop} est déjà attachée à {@code TextFragment} et est devenue en lecture seule. |
| [setAlignmentType](#setAlignmentType-int-) | Obtient ou définit une énumération {@code AlignmentType} qui indique le type d'alignement d'onglet. |
| [setLeaderType](#setLeaderType-int-) | Obtient ou définit une énumération {@code TabLeaderType} qui indique le type de leader d'onglet. |
| [setPosition](#setPosition-float-) | Définit une valeur flottante qui indique la position du tab stop. |

### TabStop {#TabStop--}
```
public TabStop()
```

Initialise une nouvelle instance de la classe {@code TabStop}.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Initialise une nouvelle instance de la classe {@code TabStop} avec la position spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position |  | La position du tab stop. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Obtient ou définit une énumération {@code AlignmentType} qui indique le type d'alignement d'onglet.

**Returns:**
Élément TabAlignmentType @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Obtient ou définit une énumération {@code TabLeaderType} qui indique le type de leader d'onglet.

**Returns:**
Élément TabLeaderType @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Obtient ou définit une valeur flottante qui indique la position du tab stop.

**Returns:**
Valeur flottante

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient la valeur indiquant que cette instance {@code TabStop} est déjà attachée à {@code TextFragment} et est devenue en lecture seule.

**Returns:**
valeur booléenne

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Obtient ou définit une énumération {@code AlignmentType} qui indique le type d'alignement d'onglet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément TabAlignmentType @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Obtient ou définit une énumération {@code TabLeaderType} qui indique le type de leader d'onglet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément TabLeaderType @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Définit une valeur flottante qui indique la position du tab stop.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |
