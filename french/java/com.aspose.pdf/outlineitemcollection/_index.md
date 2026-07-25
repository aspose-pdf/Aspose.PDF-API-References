---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une entrée de plan dans la hiérarchie du plan du document PDF."
type: docs
weight: 3270
url: /fr/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

Représente une entrée de plan dans la hiérarchie du plan du document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Initialise une nouvelle instance de cette classe en utilisant l'objet d'entrée de plan interne du moteur. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Initialise l'instance d'élément de plan en utilisant l'objet de hiérarchie racine. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Ajoute un élément d'outline à la collection. |
| [clear](#clear--) | Efface tous les éléments de la collection. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Pas encore pris en charge. Lève toujours NotImplementedException. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copie les entrées de plan dans un System.Array, en commençant à un indice particulier du System.Array. |
| [delete](#delete--) | Supprime cet élément de plan de la hiérarchie du plan du document. |
| [delete](#delete-java.lang.String-) | Supprime cet élément de plan de la hiérarchie du plan du document. |
| [get_Item](#get_Item-int-) | Obtient l'élément de plan de la collection en utilisant l'index. |
| [getAction](#getAction--) | Obtient l'action pour cet élément de plan. |
| [getBold](#getBold--) | Obtient le drapeau gras pour le texte du titre de cet élément de plan |
| [getColor](#getColor--) | Obtient la couleur du texte du titre de cet élément de plan. |
| [getDestination](#getDestination--) | Obtient la destination de cet élément de plan. |
| [getEngineDict](#getEngineDict--) | Interne uniquement |
| [getEngineObj](#getEngineObj--) | Interne uniquement |
| [getFirst](#getFirst--) | Obtient l'élément de plan représentant le premier élément de niveau supérieur dans la hiérarchie du plan. |
| [getItalic](#getItalic--) | Obtient un drapeau italique pour le texte du titre de cet élément de plan |
| [getLast](#getLast--) | Obtient l'élément de plan représentant le dernier élément de niveau supérieur dans la hiérarchie du plan. |
| [getLevel](#getLevel--) | Obtient le niveau hiérarchique de l'élément de plan. |
| [getNext](#getNext--) | Obtient l'élément de plan représentant l'élément suivant relativement à cet élément dans la hiérarchie du plan. |
| [getOpen](#getOpen--) | Obtient le statut ouvert (true/false) de l'élément de plan. |
| [getParent](#getParent--) | Obtient l'objet parent de cet élément de plan dans la hiérarchie du plan. |
| [getPrev](#getPrev--) | Obtient l'élément de plan représentant l'élément précédent relativement à cet élément dans la hiérarchie du plan. |
| [getSyncRoot](#getSyncRoot--) | Obtient l'objet qui peut être utilisé pour synchroniser l'accès à cette collection. |
| [getTitle](#getTitle--) | Obtient le titre de cet élément de plan. |
| [getVisibleCount](#getVisibleCount--) | Obtient le nombre total d'éléments de plan à tous les niveaux de la hiérarchie du plan du document. |
| [hasNext](#hasNext--) | Vérifiez si l'élément de plan représentant l'élément suivant est relatif à cet élément dans la hiérarchie du plan. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Insère l'élément de plan dans la collection à l'endroit spécifié. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Obtient la valeur indiquant si l'accès à cette collection est synchronisé (thread-safe). |
| [iterator](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [next](#next--) |  |
| [remove](#remove-int-) | Supprime l'élément par indice. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Pas encore pris en charge. Lève toujours NotImplementedException. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Définit l'action pour cet élément de plan. |
| [setBold](#setBold-boolean-) | Définit le drapeau gras pour le texte du titre de cet élément de plan. |
| [setColor](#setColor-java.awt.Color-) | Définit la couleur du texte du titre de cet élément de plan. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Définit la destination de cet élément de plan. |
| [setItalic](#setItalic-boolean-) | Définit le drapeau italique pour le texte du titre de cet élément de plan. |
| [setOpen](#setOpen-boolean-) | Définit le statut ouvert (true/false) pour l'élément de plan. |
| [setTitle](#setTitle-java.lang.String-) | Définit le titre de cet élément de plan. |
| [size](#size--) | Nombre d'éléments de la collection. Veuillez ne pas confondre avec VisibleCount : VisibleCount indique le nombre d'éléments de plan visibles à tous les niveaux. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Initialise une nouvelle instance de cette classe en utilisant l'objet d'entrée de plan interne du moteur.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Initialise l'instance d'élément de plan en utilisant l'objet de hiérarchie racine.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Ajoute un élément d'outline à la collection.

### clear {#clear--}
```
public void clear()
```

Efface tous les éléments de la collection.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Pas encore pris en charge. Lève toujours NotImplementedException.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copie les entrées de plan dans un System.Array, en commençant à un indice particulier du System.Array.

### delete {#delete--}
```
public void delete()
```

Supprime cet élément de plan de la hiérarchie du plan du document.

### delete {#delete-java.lang.String-}
Supprime cet élément de plan de la hiérarchie du plan du document.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Obtient l'élément de plan de la collection en utilisant l'index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index dans la collection. |

**Returns:**
Objet OutlineItemCollection.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Obtient l'action pour cet élément de plan.

**Returns:**
Valeur PdfAction

### getBold {#getBold--}
```
public boolean getBold()
```

Obtient le drapeau gras pour le texte du titre de cet élément de plan

**Returns:**
valeur booléenne

### getColor {#getColor--}
```
public Color getColor()
```

Obtient la couleur du texte du titre de cet élément de plan.

**Returns:**
Valeur de couleur

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Obtient la destination de cet élément de plan.

**Returns:**
Valeur IAppointment

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Interne uniquement

**Returns:**
Objet IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Interne uniquement

**Returns:**
Objet IPdfObject

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Obtient l'élément de plan représentant le premier élément de niveau supérieur dans la hiérarchie du plan.

**Returns:**
Valeur OutlineItemCollection

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Obtient un drapeau italique pour le texte du titre de cet élément de plan

**Returns:**
valeur booléenne

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Obtient l'élément de plan représentant le dernier élément de niveau supérieur dans la hiérarchie du plan.

**Returns:**
Valeur OutlineItemCollection

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtient le niveau hiérarchique de l'élément de plan.

**Returns:**
valeur int

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Obtient l'élément de plan représentant l'élément suivant relativement à cet élément dans la hiérarchie du plan.

**Returns:**
Valeur OutlineItemCollection

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtient le statut ouvert (true/false) de l'élément de plan.

**Returns:**
valeur booléenne

### getParent {#getParent--}
```
public Outlines getParent()
```

Obtient l'objet parent de cet élément de plan dans la hiérarchie du plan.

**Returns:**
Valeur Object

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Obtient l'élément de plan représentant l'élément précédent relativement à cet élément dans la hiérarchie du plan.

**Returns:**
Valeur OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient l'objet qui peut être utilisé pour synchroniser l'accès à cette collection.

**Returns:**
Valeur Object

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtient le titre de cet élément de plan.

**Returns:**
valeur String

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Obtient le nombre total d'éléments de plan à tous les niveaux de la hiérarchie du plan du document.

**Returns:**
valeur int

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Vérifiez si l'élément de plan représentant l'élément suivant est relatif à cet élément dans la hiérarchie du plan.

**Returns:**
valeur booléenne

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Insère l'élément de plan dans la collection à l'endroit spécifié.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient une valeur indiquant si la collection est en lecture seule.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtient la valeur indiquant si l'accès à cette collection est synchronisé (thread-safe).

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Returns:**
Un objet System.Collections.IEnumerator pouvant être utilisé pour parcourir la collection.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Supprime l'élément par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'élément à supprimer. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Pas encore pris en charge. Lève toujours NotImplementedException.

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Définit l'action pour cet élément de plan.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Définit le drapeau gras pour le texte du titre de cet élément de plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setColor {#setColor-java.awt.Color-}
Définit la couleur du texte du titre de cet élément de plan.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Définit la destination de cet élément de plan.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Définit le drapeau italique pour le texte du titre de cet élément de plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Définit le statut ouvert (true/false) pour l'élément de plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTitle {#setTitle-java.lang.String-}
Définit le titre de cet élément de plan.

### size {#size--}
```
public int size()
```

Nombre d'éléments de la collection. Veuillez ne pas confondre avec VisibleCount : VisibleCount indique le nombre d'éléments de plan visibles à tous les niveaux.

**Returns:**
valeur int
