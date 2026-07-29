---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente l'état d'un fragment de texte. </p> <hr> <pre> L'exemple montre comment changer la couleur du texte et la taille de police du texte avec l'objet {@code TextState}. // Open."
type: docs
weight: 5150
url: /fr/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Représente l'état d'un fragment de texte. </p> <hr> <pre> L'exemple montre comment changer la couleur du texte et la taille de police du texte avec l'objet {@code TextState}. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier la couleur de premier plan de la première occurrence du texte absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Modifier la taille de police de la première occurrence du texte absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Fournit un moyen de modifier les propriétés suivantes du texte : police ({@code TextFragmentState.Font} propriété) taille de police ({@code TextFragmentState.FontSize} propriété) style de police ({@code TextFragmentState.FontStyle} propriété) couleur de premier plan ({@code TextFragmentState.ForegroundColor} propriété) couleur d'arrière-plan ({@code TextFragmentState.BackgroundColor} propriété) </p> <p> Notez que la modification des propriétés {@code TextFragmentState} peut modifier la collection interne {@code TextFragment.Segments} car TextFragment est un objet agrégé et il peut réarranger les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection {@code TextFragment.Segments} inchangée, veuillez modifier les segments internes individuellement. </p> @see TextFragmentAbsorber @see IDocument

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Initialise une nouvelle instance de l'objet {@code TextFragmentState} avec l'objet {@code TextFragment} spécifié. Cette initialisation de {@code TextFragmentState} n'est pas prise en charge. TextFragmentState n'est disponible qu'avec la propriété {@code TextFragment.TextState}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Applique les paramètres d'un autre textState </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Applique les paramètres d'un autre textState |
| [getBackgroundColor](#getBackgroundColor--) | Définit la couleur d'arrière-plan du texte, représenté par l'objet {@code TextFragment} |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtient l'espacement des caractères du texte, représenté par l'objet {@code TextFragment}. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Obtient le drapeau indiquant si la bordure du rectangle du texte est dessinée. |
| [getFont](#getFont--) | Obtient la police du texte, représentée par l'objet {@code TextFragment} |
| [getFontSize](#getFontSize--) | Obtient la taille de la police du texte, représentée par l'objet {@code TextFragment} |
| [getFontStyle](#getFontStyle--) | Définit le style de police du texte, représenté par l'objet {@code TextFragment} |
| [getForegroundColor](#getForegroundColor--) | Obtient la couleur de premier plan du texte, représentée par l'objet {@code TextFragment} |
| [getFormattingOptions](#getFormattingOptions--) | Obtient ou définit les options de formatage. La définition des options ne sera effective que dans les scénarios de génération. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Obtient l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextFragmentState.VerticalAlignment fonctionne uniquement dans les scénarios de génération de nouveaux documents. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtient l'échelle horizontale du texte, représentée par l'objet {@code TextFragment}. |
| [getLineSpacing](#getLineSpacing--) | <p> Obtient l'espacement des lignes du texte. </p> |
| [getRenderingMode](#getRenderingMode--) | Obtient ou définit le mode de rendu du texte. |
| [getRotation](#getRotation--) | Obtient ou définit l'angle de rotation en degrés. |
| [getStrokingColor](#getStrokingColor--) | Obtient ou définit les opérations de tracé de couleur du rendu {@code TextFragment} (texte en contour, bordure du rectangle) |
| [getTabStops](#getTabStops--) | <p> Obtient les tabulations du texte. </p> <hr> <p> Notez que la propriété Tabstops fonctionne uniquement dans les scénarios de génération de nouveaux documents. Les tabulations peuvent être ajoutées lors de l'initialisation {@code TextFragment}. Les tabulations doivent être construites avant le texte. </p> |
| [getTextHeight](#getTextHeight--) | Obtient la hauteur du texte, représentée par l'objet {@code TextFragment} |
| [getWordSpacing](#getWordSpacing--) | Obtient l'espacement des mots du texte. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Vérifie si la chaîne d'entrée peut être placée à l'intérieur du rectangle défini. |
| [isInvisible](#isInvisible--) | Obtient l'invisibilité du texte. |
| [isStrikeOut](#isStrikeOut--) | Obtient ou définit le barré du texte, représenté par l'objet {@link TextFragment} |
| [isSubscript](#isSubscript--) | Obtient ou définit le texte en indice, représenté par l'objet {@code TextFragment}. |
| [isSuperscript](#isSuperscript--) | Obtient ou définit le texte en exposant, représenté par l'objet {@code TextFragment}. |
| [isUnderline](#isUnderline--) | Obtient ou définit le soulignement du texte, représenté par l'objet {@link TextFragment} |
| [measureHeight](#measureHeight-char-) | Mesure la hauteur des caractères. |
| [measureString](#measureString-java.lang.String-) | Mesure la chaîne. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Définit la couleur d'arrière-plan du texte, représenté par l'objet TextFragment |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Définit l'espacement des caractères du texte, représenté par l'objet {@code TextFragment}. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Définit le drapeau indiquant si la bordure du rectangle du texte est dessinée. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Définit la police du texte, représentée par l'objet {@code TextFragment} |
| [setFontSize](#setFontSize-float-) | Définit la taille de la police du texte, représentée par l'objet {@code TextFragment} |
| [setFontStyle](#setFontStyle-int-) | Définit le style de police du texte, représenté par l'objet {@link TextFragment} |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Définit la couleur de premier plan du texte, représentée par l'objet {@code TextFragment} |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Obtient ou définit les options de formatage. La définition des options ne sera effective que dans les scénarios de génération. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Définit l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextFragmentState.VerticalAlignment ne fonctionne que dans les scénarios de génération de nouveaux documents. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Définit le redimensionnement horizontal du texte, représenté par l'objet {@code TextFragment}. |
| [setInvisible](#setInvisible-boolean-) | Définit l'invisibilité du texte. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Définit l'espacement des lignes du texte. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Obtient ou définit le mode de rendu du texte. |
| [setRotation](#setRotation-double-) | Obtient ou définit l'angle de rotation en degrés. |
| [setStrikeOut](#setStrikeOut-boolean-) | Définit le texte barré, représenté par l'objet {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Obtient ou définit les opérations de tracé de couleur du rendu {@code TextFragment} (texte en contour, bordure du rectangle) |
| [setSubscript](#setSubscript-boolean-) | Obtient ou définit le texte en indice, représenté par l'objet {@code TextFragment}. |
| [setSuperscript](#setSuperscript-boolean-) | Obtient ou définit le texte en exposant, représenté par l'objet {@code TextFragment}. |
| [setUnderline](#setUnderline-boolean-) | Définit le texte souligné, représenté par l'objet {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Définit l'espacement des mots du texte. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Initialise une nouvelle instance de l'objet {@code TextFragmentState} avec l'objet {@code TextFragment} spécifié. Cette initialisation de {@code TextFragmentState} n'est pas prise en charge. TextFragmentState n'est disponible qu'avec la propriété {@code TextFragment.TextState}.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Applique les paramètres d'un autre textState </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Applique les paramètres d'un autre textState

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Définit la couleur d'arrière-plan du texte, représenté par l'objet {@code TextFragment}

**Returns:**
valeur d'objet Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Obtient l'espacement des caractères du texte, représenté par l'objet {@code TextFragment}.

**Returns:**
Valeur flottante

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte.

**Returns:**
Élément CoordinateOrigin

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Obtient le drapeau indiquant si la bordure du rectangle du texte est dessinée.

**Returns:**
valeur booléenne

### getFont {#getFont--}
```
public Font getFont()
```

Obtient la police du texte, représentée par l'objet {@code TextFragment}

**Returns:**
Valeur de police

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Obtient la taille de la police du texte, représentée par l'objet {@code TextFragment}

**Returns:**
Valeur flottante

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Définit le style de police du texte, représenté par l'objet {@code TextFragment}

**Returns:**
Élément FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Obtient la couleur de premier plan du texte, représentée par l'objet {@code TextFragment}

**Returns:**
Objet Color

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Obtient ou définit les options de formatage. La définition des options ne sera effective que dans les scénarios de génération.

**Returns:**
instance de TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Obtient l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextFragmentState.VerticalAlignment fonctionne uniquement dans les scénarios de génération de nouveaux documents. </p>

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Obtient l'échelle horizontale du texte, représentée par l'objet {@code TextFragment}.

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
élément TextRenderingMode

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtient ou définit l'angle de rotation en degrés.

**Returns:**
valeur double

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Obtient ou définit les opérations de tracé de couleur du rendu {@code TextFragment} (texte en contour, bordure du rectangle)

**Returns:**
Instance de Couleur

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Obtient les tabulations du texte. </p> <hr> <p> Notez que la propriété Tabstops fonctionne uniquement dans les scénarios de génération de nouveaux documents. Les tabulations peuvent être ajoutées lors de l'initialisation {@code TextFragment}. Les tabulations doivent être construites avant le texte. </p>

**Returns:**
objet TabStops

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Obtient la hauteur du texte, représentée par l'objet {@code TextFragment}

**Returns:**
Valeur flottante

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Obtient l'espacement des mots du texte.

**Returns:**
Valeur flottante

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Vérifie si la chaîne d'entrée peut être placée à l'intérieur du rectangle défini.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Obtient l'invisibilité du texte.

**Returns:**
valeur booléenne

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Obtient ou définit le barré du texte, représenté par l'objet {@link TextFragment}

**Returns:**
valeur booléenne

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Obtient ou définit le texte en indice, représenté par l'objet {@code TextFragment}.

**Returns:**
valeur booléenne

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Obtient ou définit le texte en exposant, représenté par l'objet {@code TextFragment}.

**Returns:**
valeur booléenne

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Obtient ou définit le soulignement du texte, représenté par l'objet {@link TextFragment}

**Returns:**
valeur booléenne

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Définit la couleur d'arrière-plan du texte, représenté par l'objet TextFragment

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Définit l'espacement des caractères du texte, représenté par l'objet {@code TextFragment}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Obtient ou définit le CoordinateOrigin du texte. Si CoordinateOrigin est Descender, la coordonnée Y du texte correspond au point le plus bas de la police. Si CoordinateOrigin est BaseLine, la coordonnée Y du texte correspond à la ligne de base de la police. La valeur par défaut est Descender. Si la valeur Descent de la police est trop grande, le texte peut être rendu plus haut que les autres polices. Dans ce cas, BaseLine peut être sélectionné comme CoordinateOrigin pour un meilleur rendu du texte.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Définit le drapeau indiquant si la bordure du rectangle du texte est dessinée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFont {#setFont-com.aspose.pdf.Font-}
Définit la police du texte, représentée par l'objet {@code TextFragment}

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Définit la taille de la police du texte, représentée par l'objet {@code TextFragment}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Définit le style de police du texte, représenté par l'objet {@link TextFragment}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Définit la couleur de premier plan du texte, représentée par l'objet {@code TextFragment}

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Obtient ou définit les options de formatage. La définition des options ne sera effective que dans les scénarios de génération.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Définit l'alignement horizontal du texte. </p> <hr> <p> HorizontalAlignment.None est égal à HorizontalAlignment.Left. Notez que la propriété TextFragmentState.VerticalAlignment ne fonctionne que dans les scénarios de génération de nouveaux documents. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Définit le redimensionnement horizontal du texte, représenté par l'objet {@code TextFragment}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Définit l'invisibilité du texte.

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

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Obtient ou définit l'angle de rotation en degrés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

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
Obtient ou définit les opérations de tracé de couleur du rendu {@code TextFragment} (texte en contour, bordure du rectangle)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Obtient ou définit le texte en indice, représenté par l'objet {@code TextFragment}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Obtient ou définit le texte en exposant, représenté par l'objet {@code TextFragment}.

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
