---
title: "ElementList"
linktitle: "ElementList"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une collection ordonnée d'éléments."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Représente une collection ordonnée d'éléments.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Ajouter un élément à la liste. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Obtient le nombre d'éléments dans l'ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insérer l'élément dans la liste. |
| [item](#item-int-) | Récupère un élément à l'index donné. |
| [iterator](#iterator--) | Obtient un énumérateur qui parcourt la collection d'éléments. |
| [removeAt](#removeAt-int-) | Supprimer l'élément de la liste. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Supprimer l'élément de la liste. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Ajouter un élément à la liste.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre d'éléments dans l'ElementList.

**Returns:**
valeur int

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Insérer l'élément dans la liste.

### item {#item-int-}
```
public abstract Element item(int index)
```

Récupère un élément à l'index donné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index dans la liste des éléments. |

**Returns:**
Le {@code /Aspose.Pdf.LogicalStructure.Element} avec l'index spécifié dans la collection. Si {@code index} est supérieur ou égal au nombre d'éléments dans la liste, cela renvoie null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Obtient un énumérateur qui parcourt la collection d'éléments.

**Returns:**
Un énumérateur utilisé pour parcourir la collection d'éléments.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Supprimer l'élément de la liste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index à supprimer. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Supprimer l'élément de la liste.
