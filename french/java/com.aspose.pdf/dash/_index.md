---
title: "Tiret"
linktitle: "Tiret"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant le motif de tirets de ligne."
type: docs
weight: 910
url: /fr/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Classe représentant le motif de tirets de ligne.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Dash](#Dash-int:A-) | Constructeur pour Dash. Définit un motif de tirets et d'espaces qui doit être utilisé pour dessiner une bordure en pointillés. |
| [Dash](#Dash-int-int-) | Constructeur pour Dash. Définit une bordure en pointillés avec le tiret et l'espace spécifiés, qui restent inchangés pour toute la bordure en pointillés. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getOff](#getOff--) | Obtient ou définit la longueur du premier espace entre les tirets. |
| [getOn](#getOn--) | Obtient ou définit la longueur du premier tiret. |
| [getPattern](#getPattern--) | Obtient le tableau de tirets définissant un motif de tirets et d'espaces qui doit être utilisé pour dessiner une bordure en pointillés. |
| [setOff](#setOff-int-) | Obtient ou définit la longueur du premier espace entre les tirets. |
| [setOn](#setOn-int-) | Obtient ou définit la longueur du premier tiret. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Constructeur pour Dash. Définit un motif de tirets et d'espaces qui doit être utilisé pour dessiner une bordure en pointillés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| motif |  | Un tableau de tirets (d'au moins deux valeurs) définissant un motif de tirets et d'espaces qui doit être utilisé pour dessiner une bordure en pointillés. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Constructeur pour Dash. Définit une bordure en pointillés avec le tiret et l'espace spécifiés, qui restent inchangés pour toute la bordure en pointillés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| activé |  | Longueur du tiret. |
| désactivé |  | Longueur de l'espace. |

### getOff {#getOff--}
```
public final int getOff()
```

Obtient ou définit la longueur du premier espace entre les tirets.

**Returns:**
valeur int

### getOn {#getOn--}
```
public final int getOn()
```

Obtient ou définit la longueur du premier tiret.

**Returns:**
valeur int

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Obtient le tableau de tirets définissant un motif de tirets et d'espaces qui doit être utilisé pour dessiner une bordure en pointillés.

**Returns:**
tableau d'int

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Obtient ou définit la longueur du premier espace entre les tirets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Obtient ou définit la longueur du premier tiret.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
