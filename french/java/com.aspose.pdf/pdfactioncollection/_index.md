---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe décrit liste d'actions."
type: docs
weight: 3680
url: /fr/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Classe décrit liste d'actions.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Ajoute une action à la liste d'actions. |
| [delete](#delete-int-) | Supprime l'action par indice. |
| [get_Item](#get_Item-int-) | Obtient l'action par son indice. |
| [getCount](#getCount--) | Obtient le nombre d'actions. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Méthode interne |
| [iterator](#iterator--) | Obtient l'énumérateur. |

### add {#add-com.aspose.pdf.PdfAction-}
Ajoute une action à la liste d'actions.

### delete {#delete-int-}
```
public void delete(int index)
```

Supprime l'action par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'action à supprimer. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Obtient l'action par son indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Valeur de l'indice d'action. |

**Returns:**
Indice PdfAction si trouvé ; sinon, lève @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

Obtient le nombre d'actions.

**Returns:**
valeur int

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Méthode interne

**Returns:**
objet interne.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Obtient l'énumérateur.

**Returns:**
Énumérateur PDfAction.
