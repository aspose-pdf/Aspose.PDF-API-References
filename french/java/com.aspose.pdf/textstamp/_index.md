---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un tampon textuel."
type: docs
weight: 5320
url: /fr/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Représente un tampon textuel.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Initialise une nouvelle instance de la classe {@code TextStamp} avec l'objet formattedText |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Initialise une nouvelle instance de la classe {@code TextStamp} avec l'objet formattedText |
| [TextStamp](#TextStamp-java.lang.String-) | Initialise une nouvelle instance de la classe {@code TextStamp}. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Initialise une nouvelle instance de la classe TextStamp. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Ajuste automatiquement la précision de la taille de police. Valeur par défaut : 0,1 ; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Si activé, la taille de police sera automatiquement ajustée pour s'adapter au rectangle du tampon de taille : {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) et {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La largeur et la hauteur par défaut sont dérivées du rectangle de la page. |
| [getDefaultFont](#getDefaultFont--) | Renvoie la police par défaut |
| [getDefaultFontSize](#getDefaultFontSize--) | Taille de police par défaut |
| [getDraw](#getDraw--) | Cette propriété détermine comment le tampon est dessiné sur la page. Si Draw = true, le tampon est dessiné comme des opérateurs graphiques et si draw = false, le tampon est dessiné comme du texte. |
| [getFontSize](#getFontSize--) | Taille de police réelle après le placement du tampon. (Peut différer de la taille de police initiale fournie via le constructeur si l'option 'AutoAdjustFontSizeToFitStampRectangle' est activée.) |
| [getHeight](#getHeight--) | Hauteur souhaitée du tampon sur la page. |
| [getMaxRowWidth](#getMaxRowWidth--) | Hauteur maximale de ligne pour l'option WordWrap. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Obtient ou définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés. |
| [getReplacementFont](#getReplacementFont--) | Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis. |
| [getTextAlignment](#getTextAlignment--) | Alignement du texte à l'intérieur du tampon. |
| [getTextState](#getTextState--) | Obtient les propriétés texte du tampon. Voir {@code TextState} pour plus de détails. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Définit l'origine des coordonnées pour le placement du texte. Si TreatYIndentAsBaseLine = true (valeur par défaut lorsque Draw = true), la valeur YIndent sera considérée comme la ligne de base du texte. Si TreatYIndentAsBaseLine = false (valeur par défaut lorsque Draw = false), la valeur YIndent sera considérée comme le bas (ligne de descente) du texte. |
| [getValue](#getValue--) | Obtient la valeur chaîne utilisée comme tampon sur la page. |
| [getWidth](#getWidth--) | Largeur souhaitée du tampon sur la page. |
| [getWordWrapMode](#getWordWrapMode--) | Obtient ou définit le mode de retour à la ligne pour le rendu du texte. |
| [isJustify](#isJustify--) | Définit la justification du texte. Si cette propriété est définie sur true, les bords gauche et droit du texte sont alignés. Valeur par défaut : false. |
| [isScale](#isScale--) | Définit le redimensionnement du texte. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera mis à l'échelle afin de s'adapter à la largeur spécifiée. |
| [isWordWrap](#isWordWrap--) | Définit le retour à la ligne. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera réparti sur plusieurs lignes pour s'adapter à la largeur spécifiée. Valeur par défaut : false. |
| [put](#put-com.aspose.pdf.Page-) | Ajoute un tampon textuel sur la page. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Ajuste automatiquement la précision de la taille de police. Valeur par défaut : 0,1 ; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Si activé, la taille de police sera automatiquement ajustée pour s'adapter au rectangle du tampon de taille : {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) et {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La largeur et la hauteur par défaut sont dérivées du rectangle de la page. |
| [setDraw](#setDraw-boolean-) | Cette propriété détermine comment le tampon est dessiné sur la page. Si Draw = true, le tampon est dessiné comme des opérateurs graphiques et si draw = false, le tampon est dessiné comme du texte. |
| [setHeight](#setHeight-double-) | Hauteur souhaitée du tampon sur la page. |
| [setJustify](#setJustify-boolean-) | Définit la justification du texte. Si cette propriété est définie sur true, les bords gauche et droit du texte sont alignés. Valeur par défaut : false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Hauteur maximale de ligne pour l'option WordWrap. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Obtient ou définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis. |
| [setScale](#setScale-boolean-) | Définit le redimensionnement du texte. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera mis à l'échelle afin de s'adapter à la largeur spécifiée. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Alignement du texte à l'intérieur du tampon. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Définit l'origine des coordonnées pour le placement du texte. Si TreatYIndentAsBaseLine = true (valeur par défaut lorsque Draw = true), la valeur YIndent sera considérée comme la ligne de base du texte. Si TreatYIndentAsBaseLine = false (valeur par défaut lorsque Draw = false), la valeur YIndent sera considérée comme le bas (ligne de descente) du texte. |
| [setValue](#setValue-java.lang.String-) | Définit la valeur chaîne utilisée comme tampon sur la page. |
| [setWidth](#setWidth-double-) | Largeur souhaitée du tampon sur la page. |
| [setWordWrap](#setWordWrap-boolean-) | Définit le retour à la ligne. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera réparti sur plusieurs lignes pour s'adapter à la largeur spécifiée. Valeur par défaut : false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Obtient ou définit le mode de retour à la ligne pour le rendu du texte. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Initialise une nouvelle instance de la classe {@code TextStamp} avec l'objet formattedText

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Initialise une nouvelle instance de la classe {@code TextStamp} avec l'objet formattedText

### TextStamp {#TextStamp-java.lang.String-}
Initialise une nouvelle instance de la classe {@code TextStamp}.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Initialise une nouvelle instance de la classe TextStamp.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Ajuste automatiquement la précision de la taille de police. Valeur par défaut : 0,1 ;

**Returns:**
Valeur flottante

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Si activé, la taille de police sera automatiquement ajustée pour s'adapter au rectangle du tampon de taille : {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) et {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La largeur et la hauteur par défaut sont dérivées du rectangle de la page.

**Returns:**
valeur booléenne

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Renvoie la police par défaut

**Returns:**
objet com.aspose.pdf.Font

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Taille de police par défaut

**Returns:**
Valeur flottante

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Cette propriété détermine comment le tampon est dessiné sur la page. Si Draw = true, le tampon est dessiné comme des opérateurs graphiques et si draw = false, le tampon est dessiné comme du texte.

**Returns:**
valeur booléenne

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Taille de police réelle après le placement du tampon. (Peut différer de la taille de police initiale fournie via le constructeur si l'option 'AutoAdjustFontSizeToFitStampRectangle' est activée.)

**Returns:**
Valeur flottante

### getHeight {#getHeight--}
```
public double getHeight()
```

Hauteur souhaitée du tampon sur la page.

**Returns:**
valeur double

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Hauteur maximale de ligne pour l'option WordWrap.

**Returns:**
valeur double

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Obtient ou définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés.

**Returns:**
Élément NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis.

**Returns:**
Instance Font

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Alignement du texte à l'intérieur du tampon.

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Obtient les propriétés texte du tampon. Voir {@code TextState} pour plus de détails.

**Returns:**
Élément TextState

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Définit l'origine des coordonnées pour le placement du texte. Si TreatYIndentAsBaseLine = true (valeur par défaut lorsque Draw = true), la valeur YIndent sera considérée comme la ligne de base du texte. Si TreatYIndentAsBaseLine = false (valeur par défaut lorsque Draw = false), la valeur YIndent sera considérée comme le bas (ligne de descente) du texte.

**Returns:**
valeur booléenne

### getValue {#getValue--}
```
public String getValue()
```

Obtient la valeur chaîne utilisée comme tampon sur la page.

**Returns:**
valeur String

### getWidth {#getWidth--}
```
public double getWidth()
```

Largeur souhaitée du tampon sur la page.

**Returns:**
valeur double

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Obtient ou définit le mode de retour à la ligne pour le rendu du texte.

**Returns:**
Élément WordWrapMode

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Définit la justification du texte. Si cette propriété est définie sur true, les bords gauche et droit du texte sont alignés. Valeur par défaut : false.

**Returns:**
valeur booléenne

### isScale {#isScale--}
```
public boolean isScale()
```

Définit le redimensionnement du texte. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera mis à l'échelle afin de s'adapter à la largeur spécifiée.

**Returns:**
valeur booléenne

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Définit le retour à la ligne. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera réparti sur plusieurs lignes pour s'adapter à la largeur spécifiée. Valeur par défaut : false.

**Returns:**
valeur booléenne @deprecated "Utilisez WordWrapMode à la place."

### put {#put-com.aspose.pdf.Page-}
Ajoute un tampon textuel sur la page.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Ajuste automatiquement la précision de la taille de police. Valeur par défaut : 0,1 ;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Si activé, la taille de police sera automatiquement ajustée pour s'adapter au rectangle du tampon de taille : {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) et {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). La largeur et la hauteur par défaut sont dérivées du rectangle de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Cette propriété détermine comment le tampon est dessiné sur la page. Si Draw = true, le tampon est dessiné comme des opérateurs graphiques et si draw = false, le tampon est dessiné comme du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Hauteur souhaitée du tampon sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Définit la justification du texte. Si cette propriété est définie sur true, les bords gauche et droit du texte sont alignés. Valeur par défaut : false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Hauteur maximale de ligne pour l'option WordWrap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Obtient ou définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément NoCharacterAction |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Définit le redimensionnement du texte. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera mis à l'échelle afin de s'adapter à la largeur spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Alignement du texte à l'intérieur du tampon.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Définit l'origine des coordonnées pour le placement du texte. Si TreatYIndentAsBaseLine = true (valeur par défaut lorsque Draw = true), la valeur YIndent sera considérée comme la ligne de base du texte. Si TreatYIndentAsBaseLine = false (valeur par défaut lorsque Draw = false), la valeur YIndent sera considérée comme le bas (ligne de descente) du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setValue {#setValue-java.lang.String-}
Définit la valeur chaîne utilisée comme tampon sur la page.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Largeur souhaitée du tampon sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Définit le retour à la ligne. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera réparti sur plusieurs lignes pour s'adapter à la largeur spécifiée. Valeur par défaut : false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne @deprecated "Utilisez WordWrapMode à la place." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Obtient ou définit le mode de retour à la ligne pour le rendu du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément WordWrapMode @see WordWrapMode |
