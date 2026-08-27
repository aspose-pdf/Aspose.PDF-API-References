---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un fragment html."
type: docs
weight: 1950
url: /fr/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Représente un fragment html.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Initialise une nouvelle instance de la classe HtmlFragment. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone le fragment HTML. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Obtient HtmlLoadOptions qui seront utilisés pour le chargement (et le rendu) du HTML dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation du HTML pour cette instance ou celle-ci (par ex. lorsque cette instance ou celle-ci doit utiliser un BasePath spécifique pour le HTML importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), alors les options de chargement HTML standard seront utilisées. |
| [getRectangle](#getRectangle--) | Obtient le rectangle du HtmlFragment |
| [getTextState](#getTextState--) | Obtient ou définit la police |
| [isBreakWords](#isBreakWords--) | Obtient ou définit la coupure des mots |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Obtient ou définit si le paragraphe a une marge par défaut, sinon la marge est 0 |
| [setBreakWords](#setBreakWords-boolean-) | Obtient ou définit la coupure des mots |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Définit HtmlLoadOptions qui seront utilisés pour le chargement (et le rendu) du HTML dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation du HTML pour cette instance ou celle-ci (par ex. lorsque cette instance ou celle-ci doit utiliser un BasePath spécifique pour le HTML importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), alors les options de chargement HTML standard seront utilisées. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Obtient ou définit si le paragraphe a une marge par défaut, sinon la marge est 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Obtient ou définit la police |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Initialise une nouvelle instance de la classe HtmlFragment.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone le fragment HTML.

**Returns:**
Objet fragment HTML cloné.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Obtient HtmlLoadOptions qui seront utilisés pour le chargement (et le rendu) du HTML dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation du HTML pour cette instance ou celle-ci (par ex. lorsque cette instance ou celle-ci doit utiliser un BasePath spécifique pour le HTML importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), alors les options de chargement HTML standard seront utilisées.

**Returns:**
Valeur HtmlLoadOptions

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Obtient le rectangle du HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Obtient ou définit la police

**Returns:**
Objet TextState

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Obtient ou définit la coupure des mots

**Returns:**
valeur booléenne

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Obtient ou définit si le paragraphe a une marge par défaut, sinon la marge est 0

**Returns:**
valeur booléenne

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Obtient ou définit la coupure des mots

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Définit HtmlLoadOptions qui seront utilisés pour le chargement (et le rendu) du HTML dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation du HTML pour cette instance ou celle-ci (par ex. lorsque cette instance ou celle-ci doit utiliser un BasePath spécifique pour le HTML importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), alors les options de chargement HTML standard seront utilisées.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Obtient ou définit si le paragraphe a une marge par défaut, sinon la marge est 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Obtient ou définit la police
