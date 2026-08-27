---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un objet de base abstrait pouvant être ajouté à la page (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /fr/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Représente un objet de base abstrait pouvant être ajouté à la page (doc.Paragraphs.Add()).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone cette instance. Méthode virtuelle. Retourne toujours null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtient un alignement horizontal du paragraphe |
| [getHyperlink](#getHyperlink--) | / * / * Obtient ou définit si un paragraphe est une note de bas de page. La valeur par défaut est false.(pour la génération pdf) / * / * |
| [getMargin](#getMargin--) | Obtient une marge extérieure pour le paragraphe (pour la génération pdf) |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient un alignement vertical du paragraphe |
| [getZIndex](#getZIndex--) | Obtient une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Obtient ou définit une valeur bool qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(pour la génération pdf) |
| [isInLineParagraph](#isInLineParagraph--) | Obtient si un paragraphe est inline. La valeur par défaut est false.(pour la génération pdf) |
| [isInNewPage](#isInNewPage--) | Obtient une valeur bool qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération de PDF) |
| [isKeptWithNext](#isKeptWithNext--) | Obtient une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération de PDF) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Obtient ou définit une valeur bool qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(pour la génération pdf) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit un alignement horizontal du paragraphe |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Définit le lien hypertexte (pour le générateur de PDF). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Définit qu’un paragraphe est en ligne. La valeur par défaut est false. (pour la génération de PDF) |
| [setInNewPage](#setInNewPage-boolean-) | Définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération de PDF) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération de PDF) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Définit une marge extérieure pour le paragraphe (pour la génération de PDF) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Définit un alignement vertical du paragraphe |
| [setZIndex](#setZIndex-int-) | Définit une valeur int qui indique l’ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone cette instance. Méthode virtuelle. Retourne toujours null.

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtient un alignement horizontal du paragraphe

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Obtient ou définit si un paragraphe est une note de bas de page. La valeur par défaut est false.(pour la génération pdf) / * / *

**Returns:**
valeur booléenne /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtient une marge extérieure pour le paragraphe (pour la génération pdf)

**Returns:**
Valeur MarginInfo

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtient un alignement vertical du paragraphe

**Returns:**
Élément VerticalAlignment @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Obtient une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page.

**Returns:**
valeur int

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Obtient ou définit une valeur bool qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(pour la génération pdf)

**Returns:**
valeur booléenne

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Obtient si un paragraphe est inline. La valeur par défaut est false.(pour la génération pdf)

**Returns:**
valeur booléenne

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Obtient une valeur bool qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération de PDF)

**Returns:**
valeur booléenne

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Obtient une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération de PDF)

**Returns:**
valeur booléenne

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Obtient ou définit une valeur bool qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(pour la génération pdf)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit un alignement horizontal du paragraphe

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Définit le lien hypertexte (pour le générateur de PDF).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Définit qu’un paragraphe est en ligne. La valeur par défaut est false. (pour la génération de PDF)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération de PDF)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération de PDF)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Définit une marge extérieure pour le paragraphe (pour la génération de PDF)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Définit un alignement vertical du paragraphe

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Définit une valeur int qui indique l’ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
