---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description:
type: docs
weight: 50
url: /fr/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Ajouter un élément à la liste. |
| [getCount](#getCount--) | Obtient le nombre d'éléments dans l'ElementList. |
| [item](#item-int-) | Récupère un élément à l'index donné. |
| [iterator](#iterator--) | Obtient un énumérateur qui parcourt la collection d'éléments. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Ajouter un élément à la liste.

### getCount {#getCount--}
```
public int getCount()
```

Obtient le nombre d'éléments dans l'ElementList.

**Returns:**
valeur int

### item {#item-int-}
```
public Element item(int index)
```

Récupère un élément à l'index donné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  |  |

**Returns:**
L'élément /Aspose.Pdf.LogicalStructure.Element avec l'index spécifié dans la collection. Si l'index est supérieur ou égal au nombre d'éléments dans la liste, cela renvoie null.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Obtient un énumérateur qui parcourt la collection d'éléments.

**Returns:**
Un énumérateur utilisé pour parcourir la collection d'éléments.
