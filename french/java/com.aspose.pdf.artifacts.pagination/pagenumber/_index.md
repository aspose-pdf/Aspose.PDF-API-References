---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un format de numéro de page qui inclut un index, le nombre total de pages et un délimiteur."
type: docs
weight: 150
url: /fr/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Représente un format de numéro de page qui inclut un index, le nombre total de pages et un délimiteur.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Obtient ou définit le délimiteur utilisé dans le format du numéro de page. La chaîne formatée sera mise à jour en fonction du délimiteur spécifié. |
| [getIndex](#getIndex--) | Obtient ou définit le composant d'index de page du format du numéro de page. La chaîne formatée inclura un espace réservé pour l'index de page. |
| [getOffset](#getOffset--) | Obtient ou définit le décalage à ajouter à l'index de page. |
| [getPageNumberString](#getPageNumberString-int-int-) | Renvoie une chaîne formatée représentant le numéro de page en fonction des paramètres actuels. |
| [getTotalNum](#getTotalNum--) | Obtient ou définit le composant du nombre total de pages du format du numéro de page. La chaîne formatée inclura un espace réservé pour le nombre total de pages. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Obtient ou définit le délimiteur utilisé dans le format du numéro de page. La chaîne formatée sera mise à jour en fonction du délimiteur spécifié. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Obtient ou définit le composant d'index de page du format du numéro de page. |
| [setOffset](#setOffset-int-) | Obtient ou définit le décalage à ajouter à l'index de page. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Obtient ou définit le composant du nombre total de pages du format du numéro de page. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Obtient ou définit le délimiteur utilisé dans le format du numéro de page. La chaîne formatée sera mise à jour en fonction du délimiteur spécifié.

**Returns:**
valeur String

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Obtient ou définit le composant d'index de page du format du numéro de page. La chaîne formatée inclura un espace réservé pour l'index de page.

**Returns:**
instance de PageIndex

### getOffset {#getOffset--}
```
public final int getOffset()
```

Obtient ou définit le décalage à ajouter à l'index de page.

**Returns:**
valeur int

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Renvoie une chaîne formatée représentant le numéro de page en fonction des paramètres actuels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page actuel. |
| compte |  | Le nombre total de pages. |

**Returns:**
Une chaîne de numéro de page formatée.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Obtient ou définit le composant du nombre total de pages du format du numéro de page. La chaîne formatée inclura un espace réservé pour le nombre total de pages.

**Returns:**
instance de PageTotalNum

### setDelimiter {#setDelimiter-java.lang.String-}
Obtient ou définit le délimiteur utilisé dans le format du numéro de page. La chaîne formatée sera mise à jour en fonction du délimiteur spécifié.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Obtient ou définit le composant d'index de page du format du numéro de page.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Obtient ou définit le décalage à ajouter à l'index de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Obtient ou définit le composant du nombre total de pages du format du numéro de page.
