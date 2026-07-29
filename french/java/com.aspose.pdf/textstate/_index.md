---
title: "TextState"
linktitle: "TextState"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'état du texte"
type: docs
weight: 5340
url: /fr/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Représente l'état du texte

## Champs

| Champ | Description |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Valeur par défaut de la tabulation dans les largeurs du caractère espace de la police par défaut. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextState](#TextState--) | Crée un objet d'état du texte. |
| [TextState](#TextState-java.awt.Color-) | Crée un objet d'état du texte. |
| [TextState](#TextState-java.awt.Color-double-) | Crée un objet d'état du texte. |
| [TextState](#TextState-double-) | Crée un objet d'état du texte avec spécification de la taille de police. |
| [TextState](#TextState-java.lang.String-) | Crée un objet d'état du texte. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Crée un objet d'état du texte. |
| [TextState](#TextState-java.lang.String-double-) | Crée un objet d'état du texte. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Applique les paramètres d'un autre textState </p> <hr> <p> Seules les propriétés qui ont été modifiées explicitement seront copiées. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Calcule la taille de police pour le rectangle. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Obtient la couleur d'arrière-plan du texte. </p> <hr> <p> Notez que la valeur n'est pas conservée comme une caractéristique du texte dans le document. Le getter de la propriété BackgroundColor fonctionne pour un objet dans le cas où il a été explicitement défini auparavant avec le setter BackgroundColor pour cet objet. La propriété est utilisée par le runtime dans le contexte du processus de génération/modification en cours. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtient l'espacement des caractères du texte. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte. |
| [getFont](#getFont--) | Obtient la police du texte. |
| [getfontSize](#getfontSize--) | Représente la méthode getfontSize |
| [getFontSize](#getFontSize--) | Obtient la taille de police du texte. |
| [getFontStyle](#getFontStyle--) | Définit le style de police du texte. |
| [getForegroundColor](#getForegroundColor--) | Obtient la couleur de premier plan du texte. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Obtient l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextState.HorizontalAlignment ne fonctionne que dans les scénarios de génération de nouveaux documents. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtient l'échelle horizontale du texte. |
| [getLineSpacing](#getLineSpacing--) | <p> Obtient l'espacement des lignes du texte. </p> |
| [getRenderingMode](#getRenderingMode--) | Obtient ou définit le mode de rendu du texte. |
| [getStrokingColor](#getStrokingColor--) | Obtient ou définit la couleur de premier plan du texte. |
| [getTabTag](#getTabTag--) | <p> Vous pouvez placer cette balise dans le texte pour déclarer une tabulation. </p> <hr> <p> Elle n'a d'effet qu'en combinaison avec {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Obtient la hauteur du texte. |
| [getWordSpacing](#getWordSpacing--) | Obtient l'espacement des mots du texte. |
| [isInvisible](#isInvisible--) | Obtient l'invisibilité du texte. Cela reflète essentiellement l'état {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), sauf dans certains cas particuliers (comme le rognage). |
| [isStrikeOut](#isStrikeOut--) | Obtient le texte barré, représenté par l'objet {@code TextFragment} |
| [isSubscript](#isSubscript--) | Obtient ou définit le texte en indice. |
| [isSuperscript](#isSuperscript--) | Obtient le texte en exposant. |
| [isUnderline](#isUnderline--) | Obtient le texte souligné, représenté par l'objet {@code TextFragment} |
| [measureHeight](#measureHeight-char-) | Mesure la hauteur des caractères. |
| [measureString](#measureString-java.lang.String-) | Mesure la chaîne. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Mesure la chaîne. </p> <hr> <p> insideLine indique que la chaîne n'est pas terminée. dans le cas où une partie de la chaîne complète est mesurée - insideLine doit être vrai. dans le cas où la chaîne complète est mesurée, insideLine doit être faux. en d'autres termes : si insideLine = true, seules les largeurs des caractères sont prises en compte. aucune transformation supplémentaire n'est prise en compte si insideLine = false. la fin de la chaîne est correctement gérée - la transformation italique est prise en compte. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Définit la couleur d'arrière-plan du texte. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Définit l'espacement des caractères du texte. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Obtient la police du texte. |
| [setFontSize](#setFontSize-float-) | Définit la taille de police du texte. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Définit la taille de police du texte avec mise à jour supprimée. |
| [setFontStyle](#setFontStyle-int-) | Définit le style de police du texte. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Obtient la police du texte avec mise à jour supprimée. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Définit la couleur de premier plan du texte. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Définit l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextState.HorizontalAlignment ne fonctionne que dans les scénarios de génération de nouveaux documents. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Définit l'échelle horizontale du texte. |
| [setInvisible](#setInvisible-boolean-) | Définit l'invisibilité du texte. Cela reflète essentiellement l'état {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) sauf dans certains cas particuliers (comme le rognage). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Définit l'espacement des lignes du texte. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Obtient ou définit le mode de rendu du texte. |
| [setStrikeOut](#setStrikeOut-boolean-) | Définit le texte barré, représenté par l'objet {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Obtient ou définit la couleur de premier plan du texte. |
| [setSubscript](#setSubscript-boolean-) | Obtient ou définit le texte en indice. |
| [setSuperscript](#setSuperscript-boolean-) | Définit le texte en exposant. |
| [setUnderline](#setUnderline-boolean-) | Définit le texte souligné, représenté par l'objet {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Définit l'espacement des mots du texte. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Valeur par défaut de la tabulation dans les largeurs du caractère espace de la police par défaut.

### TextState {#TextState--}
```
public TextState()
```

Crée un objet d'état du texte.

### TextState {#TextState-java.awt.Color-}
Crée un objet d'état du texte.

### TextState {#TextState-java.awt.Color-double-}
Crée un objet d'état du texte.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Crée un objet d'état du texte avec spécification de la taille de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize |  | Taille de la police. |

### TextState {#TextState-java.lang.String-}
Crée un objet d'état du texte.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Crée un objet d'état du texte.

### TextState {#TextState-java.lang.String-double-}
Crée un objet d'état du texte.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Applique les paramètres d'un autre textState </p> <hr> <p> Seules les propriétés qui ont été modifiées explicitement seront copiées. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Calcule la taille de police pour le rectangle.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Obtient la couleur d'arrière-plan du texte. </p> <hr> <p> Notez que la valeur n'est pas conservée comme une caractéristique du texte dans le document. Le getter de la propriété BackgroundColor fonctionne pour un objet dans le cas où il a été explicitement défini auparavant avec le setter BackgroundColor pour cet objet. La propriété est utilisée par le runtime dans le contexte du processus de génération/modification en cours. </p>

**Returns:**
Valeur de couleur

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Obtient l'espacement des caractères du texte.

**Returns:**
Valeur flottante

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte.

**Returns:**
Élément CoordinateOrigin

### getFont {#getFont--}
```
public Font getFont()
```

Obtient la police du texte.

**Returns:**
Objet Font

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Représente la méthode getfontSize

**Returns:**
Valeur flottante

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Obtient la taille de police du texte.

**Returns:**
Valeur flottante

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Définit le style de police du texte.

**Returns:**
Élément FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Obtient la couleur de premier plan du texte.

**Returns:**
Valeur de couleur

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Obtient l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextState.HorizontalAlignment ne fonctionne que dans les scénarios de génération de nouveaux documents. </p>

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Obtient l'échelle horizontale du texte.

**Returns:**
Valeur flottante

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Obtient l'espacement des lignes du texte. </p>

**Returns:**
float value <hr> <p> Notez que la valeur n'est pas conservée comme caractéristique du texte dans le document. Le getter de la propriété LineSpacing fonctionne pour un objet si elle a été explicitement définie auparavant avec le setter LineSpacing pour cet objet. La propriété est utilisée par le runtime dans le contexte du processus actuel de génération/modification. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Obtient ou définit le mode de rendu du texte.

**Returns:**
Élément TextRenderingMode @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Obtient ou définit la couleur de premier plan du texte.

**Returns:**
Instance de Couleur

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Vous pouvez placer cette balise dans le texte pour déclarer une tabulation. </p> <hr> <p> Elle n'a d'effet qu'en combinaison avec {@code TabStops}. </p>

**Returns:**
Valeur de chaîne "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Obtient la hauteur du texte.

**Returns:**
Valeur flottante

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Obtient l'espacement des mots du texte.

**Returns:**
Valeur flottante

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Obtient l'invisibilité du texte. Cela reflète essentiellement l'état {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), sauf dans certains cas particuliers (comme le rognage).

**Returns:**
valeur booléenne

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Obtient le texte barré, représenté par l'objet {@code TextFragment}

**Returns:**
valeur booléenne

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Obtient ou définit le texte en indice.

**Returns:**
valeur booléenne

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Obtient le texte en exposant.

**Returns:**
valeur booléenne

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Obtient le texte souligné, représenté par l'objet {@code TextFragment}

**Returns:**
valeur booléenne

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

Mesure la hauteur des caractères.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| caractère |  | Caractère à mesurer. |

**Returns:**
Hauteur du caractère si nous pouvons l'obtenir à partir de la police ; sinon 0.

### measureString {#measureString-java.lang.String-}
Mesure la chaîne.

### measureString {#measureString-java.lang.String-boolean-}
<p> Mesure la chaîne. </p> <hr> <p> insideLine indique que la chaîne n'est pas terminée. dans le cas où une partie de la chaîne complète est mesurée - insideLine doit être vrai. dans le cas où la chaîne complète est mesurée, insideLine doit être faux. en d'autres termes : si insideLine = true, seules les largeurs des caractères sont prises en compte. aucune transformation supplémentaire n'est prise en compte si insideLine = false. la fin de la chaîne est correctement gérée - la transformation italique est prise en compte. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Définit la couleur d'arrière-plan du texte.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Définit l'espacement des caractères du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte.

### setFont {#setFont-com.aspose.pdf.Font-}
Obtient la police du texte.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Définit la taille de police du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Définit la taille de police du texte avec mise à jour supprimée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Définit le style de police du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur FontStyles @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Obtient la police du texte avec mise à jour supprimée.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Définit la couleur de premier plan du texte.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Définit l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextState.HorizontalAlignment ne fonctionne que dans les scénarios de génération de nouveaux documents. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Définit l'échelle horizontale du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Définit l'invisibilité du texte. Cela reflète essentiellement l'état {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}) sauf dans certains cas particuliers (comme le rognage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Définit l'espacement des lignes du texte. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | float value <hr> <p> Notez que la valeur n'est pas conservée comme caractéristique du texte dans le document. Le getter de la propriété LineSpacing fonctionne pour un objet si elle a été explicitement définie auparavant avec le setter LineSpacing pour cet objet. La propriété est utilisée par le runtime dans le contexte du processus actuel de génération/modification. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Obtient ou définit le mode de rendu du texte.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Définit le texte barré, représenté par l'objet {@code TextFragment}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Obtient ou définit la couleur de premier plan du texte.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Obtient ou définit le texte en indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Définit le texte en exposant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Définit le texte souligné, représenté par l'objet {@code TextFragment}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Définit l'espacement des mots du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |
