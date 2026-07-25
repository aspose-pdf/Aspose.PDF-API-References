---
title: "TabStops"
linktitle: "TabStops"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une collection d'objets {@code TabStop}."
type: docs
weight: 4850
url: /fr/java/com.aspose.pdf/tabstops/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStops

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TabStops extends Object implements com.aspose.ms.System.ICloneable
```

Représente une collection d'objets {@code TabStop}.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TabStops](#TabStops--) | Initialise une nouvelle instance de la classe {@code TabStops}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add--) | Initialise une nouvelle instance de la classe {@code TabStop} et l'ajoute à la collection TabStops. |
| [add](#add-float-) | Initialise une nouvelle instance de la classe {@code TabStop} avec la position spécifiée et l'ajoute à la collection TabStops. |
| [add](#add-float-int-) | Initialise une nouvelle instance de la classe {@code TabStop} avec la position spécifiée et le type de leader et l'ajoute à la collection TabStops. |
| [add](#add-com.aspose.pdf.TabStop-) | Initialise une nouvelle instance de la classe {@code TabStop} et l'ajoute à la collection TabStops. |
| [deepClone](#deepClone--) | Clone de nouveaux objets {@code TabStops}. |
| [get_Item](#get_Item-int-) | Obtient un objet {@code TabStop} de la collection selon l'index TabStop. |
| [getCount](#getCount--) | Renvoie le nombre de tabStops |
| [isReadOnly](#isReadOnly--) | Obtient la valeur indiquant que cette instance {@code TabStops} est déjà attachée à {@code TextFragment} et est devenue en lecture seule. |
| [set_Item](#set_Item-int-com.aspose.pdf.TabStop-) | Définit un objet {@code TabStop} de la collection selon l'index du TabStop. |

### TabStops {#TabStops--}
```
public TabStops()
```

Initialise une nouvelle instance de la classe {@code TabStops}.

### add {#add--}
```
public TabStop add()
```

Initialise une nouvelle instance de la classe {@code TabStop} et l'ajoute à la collection TabStops.

**Returns:**
Le nouvel objet {@code TabStop}.

### add {#add-float-}
```
public TabStop add(float position)
```

Initialise une nouvelle instance de la classe {@code TabStop} avec la position spécifiée et l'ajoute à la collection TabStops.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position |  | La position du tab stop. |

**Returns:**
Le nouvel objet {@code TabStop}.

### add {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```

Initialise une nouvelle instance de la classe {@code TabStop} avec la position spécifiée et le type de leader et l'ajoute à la collection TabStops.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position |  | La position du tab stop. |
| leaderType |  | Le type de leader du tab stop. |

**Returns:**
Le nouvel objet {@code TabStop}.

### add {#add-com.aspose.pdf.TabStop-}
Initialise une nouvelle instance de la classe {@code TabStop} et l'ajoute à la collection TabStops.

**Returns:**
Le nouvel objet {@code TabStop}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone de nouveaux objets {@code TabStops}.

**Returns:**
Le nouvel objet {@code TabStops}.

### get_Item {#get_Item-int-}
```
public TabStop get_Item(int index)
```

Obtient un objet {@code TabStop} de la collection selon l'index TabStop.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice basé sur zéro de l'élément dans la collection {@code TabStops}. |

**Returns:**
Objet {@code TabStop}.

### getCount {#getCount--}
```
public int getCount()
```

Renvoie le nombre de tabStops

**Returns:**
valeur int

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient la valeur indiquant que cette instance {@code TabStops} est déjà attachée à {@code TextFragment} et est devenue en lecture seule.

**Returns:**
valeur booléenne

### set_Item {#set_Item-int-com.aspose.pdf.TabStop-}
Définit un objet {@code TabStop} de la collection selon l'index du TabStop.
