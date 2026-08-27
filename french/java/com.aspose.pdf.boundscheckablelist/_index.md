---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente BoundsCheckableList - un wrapper autour de System.Collections.Generic.List."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Représente BoundsCheckableList - un wrapper autour de System.Collections.Generic.List.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Initialise une nouvelle instance de la classe BoundsCheckableList. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Initialise une nouvelle instance de la classe BoundsCheckableList. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addItem](#addItem-T-) | Ajoute un objet à la fin de System.Collections.Generic.List en fonction du paramètre \"boundsCheckMode\". |
| [clear](#clear--) | Supprime tous les éléments de System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Détermine si un élément se trouve dans System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Copie l'intégralité de System.Collections.Generic.List dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible. |
| [get_Item](#get_Item-int-) | Obtient ou définit le paragraphe depuis ou vers la collection. |
| [indexOfItem](#indexOfItem-T-) | Recherche l'objet spécifié et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Insère un élément dans System.Collections.Generic.List à l'index spécifié. |
| [isReadOnly](#isReadOnly--) | Obtient la valeur indiquant si la collection est en lecture seule. |
| [iterator](#iterator--) | Renvoie un énumérateur qui parcourt System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Supprime l'élément à l'index spécifié de la System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Supprime la première occurrence d'un objet spécifique de la System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Obtient ou définit le paragraphe depuis ou vers la collection. |
| [size](#size--) | Obtient le nombre d'éléments contenus dans la System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Met à jour le paramètre boundsCheckMode pour la collection initialisée. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Met à jour le paramètre boundsCheckMode pour la collection initialisée. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Initialise une nouvelle instance de la classe BoundsCheckableList.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Initialise une nouvelle instance de la classe BoundsCheckableList.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| boundsCheckMode |  | Le mode de vérification des limites. |
| containerWidth |  | La largeur du conteneur. |
| containerHeight |  | La hauteur du conteneur. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Ajoute un objet à la fin de System.Collections.Generic.List en fonction du paramètre \"boundsCheckMode\".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item |  | L'objet à ajouter à la fin de la System.Collections.Generic.List. La valeur peut être "null" pour les types de référence. |

### clear {#clear--}
```
public final void clear()
```

Supprime tous les éléments de System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Détermine si un élément se trouve dans System.Collections.Generic.List.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item |  | L'objet à rechercher dans la System.Collections.Generic.List. La valeur peut être null pour les types de référence. |

**Returns:**
true si itemitem est trouvé dans la System.Collections.Generic.List ; sinon, false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Copie l'intégralité de System.Collections.Generic.List dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array |  | Le System.Array unidimensionnel qui est la destination des éléments copiés depuis la System.Collections.Generic.List. Le System.Array doit avoir un indexage à base zéro. |
| arrayIndex |  | L'index à base zéro dans array où la copie commence. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Obtient ou définit le paragraphe depuis ou vers la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index du paragraphe. |

**Returns:**
l'élément à l'index spécifié.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Recherche l'objet spécifié et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de System.Collections.Generic.List.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item |  | L'objet à rechercher dans la System.Collections.Generic.List. La valeur peut être null pour les types de référence. |

**Returns:**
L'index à base zéro de la première occurrence de itemitem dans l'ensemble de la System.Collections.Generic.List, si trouvé ; sinon, –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Insère un élément dans System.Collections.Generic.List à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index à base zéro où l'item doit être inséré. |
| item |  | L'objet à insérer. La valeur peut être nulle pour les types de référence. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient la valeur indiquant si la collection est en lecture seule.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Renvoie un énumérateur qui parcourt System.Collections.Generic.List.

**Returns:**
Un énumérateur pour le System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la System.Collections.Generic.List.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index basé sur zéro de l'élément à supprimer. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Supprime la première occurrence d'un objet spécifique de la System.Collections.Generic.List.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item |  | L'objet à supprimer du System.Collections.Generic.List. La valeur peut être nulle pour les types de référence. |

**Returns:**
true si itemitem est supprimé avec succès ; sinon, false. Cette méthode renvoie également false si itemitem n'a pas été trouvé dans le System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Obtient ou définit le paragraphe depuis ou vers la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index du paragraphe. |

### size {#size--}
```
public final int size()
```

Obtient le nombre d'éléments contenus dans la System.Collections.Generic.List.

**Returns:**
Le nombre d'éléments contenus dans le System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Met à jour le paramètre boundsCheckMode pour la collection initialisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| boundsCheckMode |  | Le mode de vérification des limites. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Met à jour le paramètre boundsCheckMode pour la collection initialisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| boundsCheckMode |  | Le mode de vérification des limites. |
| containerWidth |  | La largeur du conteneur. |
| containerHeight |  | La hauteur du conteneur. |
