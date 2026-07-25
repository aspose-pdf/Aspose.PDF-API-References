---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de remplacement de texte"
type: docs
weight: 5250
url: /fr/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Représente les options de remplacement de texte

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour le réglage et la portée par défaut : ReplaceAdjustment.None et Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour l'action après remplacement spécifiée. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour le réglage et la portée par défaut : ReplaceAdjustment.None et Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour le réglage et la portée par défaut : ReplaceAdjustment.None et Scope.REPLACE_FIRST |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Obtient ou définit la valeur de l'espacement des lignes utilisé si le réglage de remplacement est forcé de créer une nouvelle ligne de texte. La valeur attendue est un multiplicateur de la taille de police du texte remplacé. La valeur par défaut est 1,2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Obtient ou définit la politique d'ajustement de la taille de police pour s'adapter aux limites définies par {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | Obtient le réglage de la position gauche pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = IsFormFillingMode ; |
| [getRectangle](#getRectangle--) | Obtient ou définit le rectangle pour adapter le texte après le remplacement. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Obtient une action qui sera effectuée après le remplacement d'un fragment de texte pour le raccourcir. |
| [getReplaceScope](#getReplaceScope--) | Obtient la portée où l'opération de remplacement de texte est appliquée |
| [getRightAdjustment](#getRightAdjustment--) | Définit ou obtient le réglage de la position droite pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = WholeWordsHyphenation ; - ReplaceAdjustmentAction = IsFormFillingMode ; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Obtient ou définit une valeur indiquant s'il faut ignorer les paragraphes distincts lors de l'ajustement du texte sur la page après le remplacement du texte. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Obtient ou définit la valeur de l'espacement des lignes utilisé si le réglage de remplacement est forcé de créer une nouvelle ligne de texte. La valeur attendue est un multiplicateur de la taille de police du texte remplacé. La valeur par défaut est 1,2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Obtient ou définit la politique d'ajustement de la taille de police pour s'adapter aux limites définies par TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Obtient ou définit une valeur indiquant s'il faut ignorer les paragraphes distincts lors de l'ajustement du texte sur la page après le remplacement du texte. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Définit ou obtient le réglage de la position gauche pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = IsFormFillingMode ; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Obtient ou définit le rectangle pour adapter le texte après le remplacement. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Définit une action qui sera effectuée après le remplacement d'un fragment de texte pour le raccourcir. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Définit la portée où l'opération de remplacement de texte est appliquée |
| [setRightAdjustment](#setRightAdjustment-double-) | Définit le réglage de la position droite pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = WholeWordsHyphenation ; - ReplaceAdjustmentAction = IsFormFillingMode ; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour le réglage et la portée par défaut : ReplaceAdjustment.None et Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour l'action après remplacement spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ajustement |  | Objet ReplaceAdjustment. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour le réglage et la portée par défaut : ReplaceAdjustment.None et Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Initialise une nouvelle instance de l'objet {@code TextReplaceOptions} pour le réglage et la portée par défaut : ReplaceAdjustment.None et Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Obtient ou définit la valeur de l'espacement des lignes utilisé si le réglage de remplacement est forcé de créer une nouvelle ligne de texte. La valeur attendue est un multiplicateur de la taille de police du texte remplacé. La valeur par défaut est 1,2.

**Returns:**
valeur double

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Obtient ou définit la politique d'ajustement de la taille de police pour s'adapter aux limites définies par {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
Élément FontSizeAdjustment

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Obtient le réglage de la position gauche pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = IsFormFillingMode ;

**Returns:**
valeur double

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Obtient ou définit le rectangle pour adapter le texte après le remplacement.

**Returns:**
Instance de Rectangle

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Obtient une action qui sera effectuée après le remplacement d'un fragment de texte pour le raccourcir.

**Returns:**
Élément ReplaceAdjustment @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Obtient la portée où l'opération de remplacement de texte est appliquée

**Returns:**
Valeur int @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Définit ou obtient le réglage de la position droite pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = WholeWordsHyphenation ; - ReplaceAdjustmentAction = IsFormFillingMode ;

**Returns:**
valeur double

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Obtient ou définit une valeur indiquant s'il faut ignorer les paragraphes distincts lors de l'ajustement du texte sur la page après le remplacement du texte.

**Returns:**
boolean valeur

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Obtient ou définit la valeur de l'espacement des lignes utilisé si le réglage de remplacement est forcé de créer une nouvelle ligne de texte. La valeur attendue est un multiplicateur de la taille de police du texte remplacé. La valeur par défaut est 1,2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Obtient ou définit la politique d'ajustement de la taille de police pour s'adapter aux limites définies par TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Obtient ou définit une valeur indiquant s'il faut ignorer les paragraphes distincts lors de l'ajustement du texte sur la page après le remplacement du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Définit ou obtient le réglage de la position gauche pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = IsFormFillingMode ;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Obtient ou définit le rectangle pour adapter le texte après le remplacement.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Définit une action qui sera effectuée après le remplacement d'un fragment de texte pour le raccourcir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ReplaceAdjustment @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Définit la portée où l'opération de remplacement de texte est appliquée

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

Définit le réglage de la position droite pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = WholeWordsHyphenation ; - ReplaceAdjustmentAction = IsFormFillingMode ;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |
