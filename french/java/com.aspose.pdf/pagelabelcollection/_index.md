---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant la collection de page label."
type: docs
weight: 3400
url: /fr/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Classe représentant la collection de page label.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getLabel](#getLabel-int-) | Obtient l'étiquette de page par indice de page (l'indice de page commence à 0). |
| [getPages](#getPages--) | Obtient les indices de page dans la collection. |
| [removeLabel](#removeLabel-int-) | Supprime l'étiquette par indice de page (l'indice de page commence à 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Met à jour l'étiquette pour l'indice de page donné (l'indice de page commence à 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Obtient l'étiquette de page par indice de page (l'indice de page commence à 0).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageIndex |  | Indice de la page. |

**Returns:**
Étiquette de page pour l'indice de page spécifié ou null si l'étiquette de page n'existe pas.

### getPages {#getPages--}
```
public int[] getPages()
```

Obtient les indices de page dans la collection.

**Returns:**
Tableau d'entiers contenant les indices des pages.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Supprime l'étiquette par indice de page (l'indice de page commence à 0).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageIndex |  | Indice de la page où l'étiquette doit être supprimée. |

**Returns:**
true si l'opération s'est exécutée avec succès.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Met à jour l'étiquette pour l'indice de page donné (l'indice de page commence à 0).
