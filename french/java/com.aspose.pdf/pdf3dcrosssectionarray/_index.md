---
title: "PDF3DCrossSectionArray"
linktitle: "PDF3DCrossSectionArray"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe PDF3DCrossSectionArray."
type: docs
weight: 3600
url: /fr/java/com.aspose.pdf/pdf3dcrosssectionarray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSectionArray

```
public class PDF3DCrossSectionArray extends Object
```

Classe PDF3DCrossSectionArray.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PDF3DCrossSectionArray](#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-) | Initialise une nouvelle instance de la classe {@code PDF3DCrossSectionArray}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.PDF3DCrossSection-) | Ajoute la section transversale spécifiée au tableau des vues. |
| [get_Item](#get_Item-int-) | Obtient ou définit le {@code PDF3DCrossSection} à l'indice spécifié. |
| [getCount](#getCount--) | Obtient le nombre de sections transversales. |
| [removeAll](#removeAll--) | Supprime toutes les sections transversales du tableau. |
| [removeAt](#removeAt-int-) | Supprime la section transversale du tableau à l'indice spécifié. |
| [set_Item](#set_Item-int-com.aspose.pdf.PDF3DCrossSection-) | Obtient ou définit le {@code PDF3DCrossSection} à l'indice spécifié. |

### PDF3DCrossSectionArray {#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-}
Initialise une nouvelle instance de la classe {@code PDF3DCrossSectionArray}.

### add {#add-com.aspose.pdf.PDF3DCrossSection-}
Ajoute la section transversale spécifiée au tableau des vues.

### get_Item {#get_Item-int-}
```
public PDF3DCrossSection get_Item(int index)
```

Obtient ou définit le {@code PDF3DCrossSection} à l'indice spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index. |

**Returns:**
Coupe transversale. @throws IndexOutOfRangeException Index invalide : l'index doit être dans la plage [1..n] où n est égal au nombre de coupes transversales.

### getCount {#getCount--}
```
public int getCount()
```

Obtient le nombre de sections transversales.

**Returns:**
int value : Le nombre de coupes transversales.

### removeAll {#removeAll--}
```
public void removeAll()
```

Supprime toutes les sections transversales du tableau.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Supprime la section transversale du tableau à l'indice spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'index de la coupe transversale supprimée dans le tableau. @throws IndexOutOfRangeException Index invalide : l'index doit être dans la plage [1..n] où n est égal au nombre de coupes transversales. |

### set_Item {#set_Item-int-com.aspose.pdf.PDF3DCrossSection-}
Obtient ou définit le {@code PDF3DCrossSection} à l'indice spécifié.
