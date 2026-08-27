---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente les paragraphes de texte comme un objet texte multilignes. </p> <hr> <pre> L'exemple montre comment créer un objet paragraphe de texte et l'ajouter à la page Pdf. Document doc."
type: docs
weight: 5200
url: /fr/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Représente les paragraphes de texte comme un objet texte multiligne. </p> <hr> <pre> L'exemple montre comment créer un objet paragraphe de texte et l'ajouter à la page Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // créer un paragraphe de texte TextParagraph paragraph = new TextParagraph(); // définir le rectangle du paragraphe paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // définir les options de retour à la ligne paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // ajouter des lignes de chaîne paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // ajouter le paragraphe à la page Pdf avec le TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // enregistrer le document Pdf doc.save(outFile); </pre>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Crée l'objet {@code TextParagraph}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Ajoute une ligne de texte |
| [appendLine](#appendLine-java.lang.String-float-) | Ajoute une ligne de texte. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Ajoute une ligne de texte avec des paramètres d'état du texte. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Ajoute une ligne de texte avec des paramètres d'état du texte |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Ajoute une ligne de texte avec des paramètres d'état du texte. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Ajoute une ligne de texte avec des paramètres d'état du texte. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Ajoute une ligne de texte avec des paramètres d'état du texte |
| [beginEdit](#beginEdit--) | Commence l'édition du TextParagraph. <p> Améliore les performances du remplissage du TextParagraph. Tout calcul de mise en page est suspendu jusqu'à ce que la méthode EndEdit soit invoquée. <p> Notez que l'appel de la méthode ne peut pas être imbriqué. </p> |
| [endEdit](#endEdit--) | Termine l'édition du TextParagraph. <p> Améliore les performances du remplissage du TextParagraph. Tout calcul de mise en page est suspendu jusqu'à ce que la méthode EndEdit soit invoquée. <p> Notez que l'appel de la méthode ne peut pas être imbriqué. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Obtient ou définit la valeur du retrait des lignes suivantes. Si elle est définie sur une valeur non nulle, elle a un avantage par rapport à la valeur FormattingOptions.SubsequentLinesIndent. |
| [getFormattingOptions](#getFormattingOptions--) | Obtient les options de formatage. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtient l'alignement horizontal du texte à l'intérieur du Rectangle du paragraphe. HorizontalAlignment.None est équivalent à HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Obtient le symbole de trait d'union utilisé dans le processus de césure. Le symbole de césure est \"-\" par défaut. Pour éliminer le dessin du trait d'union (tout en conservant la procédure de retour à la ligne), veuillez définir une chaîne vide string.Empty pour HyphenSymbol. |
| [getMargin](#getMargin--) | Obtient le remplissage. |
| [getPosition](#getPosition--) | Obtient la position du paragraphe. |
| [getRectangle](#getRectangle--) | Obtient le rectangle du paragraphe. |
| [getRotation](#getRotation--) | Obtient ou définit l'angle de rotation en degrés. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Obtient la valeur du retrait des lignes suivantes. |
| [getTextRectangle](#getTextRectangle--) | Obtient le rectangle du texte placé dans le paragraphe. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Obtient l'alignement vertical du texte à l'intérieur du {@code Rectangle} du paragraphe. </p> |
| [isJustify](#isJustify--) | Obtient la valeur indiquant si le texte est justifié. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Définit la couleur d'arrière-plan pour le paragraphe de texte. |
| [setBackgroundMode](#setBackgroundMode-int-) | Définit le mode d'arrière-plan pour le paragraphe de texte |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Obtient ou définit la valeur du retrait des lignes suivantes. Si elle est définie sur une valeur non nulle, elle a un avantage par rapport à la valeur FormattingOptions.SubsequentLinesIndent. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Définit les options de formatage. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit l'alignement horizontal du texte à l'intérieur du Rectangle du paragraphe. HorizontalAlignment.None est équivalent à HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Définit le symbole de trait d'union utilisé dans le processus de césure. Le symbole de césure est \"-\" par défaut. Pour éliminer le dessin du trait d'union (tout en conservant la procédure de retour à la ligne), veuillez définir une chaîne vide string.Empty pour HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | Définit la valeur indiquant si le texte est justifié. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Définit le remplissage. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Définit la rotation du paragraphe. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Définit le mode de compatibilité avec l'ancien code |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Définit la position du paragraphe. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Définit le rectangle du paragraphe. |
| [setRotation](#setRotation-double-) | Obtient ou définit l'angle de rotation en degrés. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Définit la valeur du retrait des lignes suivantes. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Définit l'alignement vertical du texte à l'intérieur du {@code Rectangle} du paragraphe. VerticalAlignment.None est équivalent à VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Crée l'objet {@code TextParagraph}.

### appendLine {#appendLine-java.lang.String-}
Ajoute une ligne de texte

### appendLine {#appendLine-java.lang.String-float-}
Ajoute une ligne de texte.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Ajoute une ligne de texte avec des paramètres d'état du texte.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Ajoute une ligne de texte avec des paramètres d'état du texte

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Ajoute une ligne de texte avec des paramètres d'état du texte.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Ajoute une ligne de texte avec des paramètres d'état du texte.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Ajoute une ligne de texte avec des paramètres d'état du texte

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Commence l'édition du TextParagraph. <p> Améliore les performances du remplissage du TextParagraph. Tout calcul de mise en page est suspendu jusqu'à ce que la méthode EndEdit soit invoquée. <p> Notez que l'appel de la méthode ne peut pas être imbriqué. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Termine l'édition du TextParagraph. <p> Améliore les performances du remplissage du TextParagraph. Tout calcul de mise en page est suspendu jusqu'à ce que la méthode EndEdit soit invoquée. <p> Notez que l'appel de la méthode ne peut pas être imbriqué. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Obtient ou définit la valeur du retrait des lignes suivantes. Si elle est définie sur une valeur non nulle, elle a un avantage par rapport à la valeur FormattingOptions.SubsequentLinesIndent.

**Returns:**
Valeur flottante

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Obtient les options de formatage.

**Returns:**
Objet TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtient l'alignement horizontal du texte à l'intérieur du Rectangle du paragraphe. HorizontalAlignment.None est équivalent à HorizontalAlignment.Left.

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Obtient le symbole de trait d'union utilisé dans le processus de césure. Le symbole de césure est \"-\" par défaut. Pour éliminer le dessin du trait d'union (tout en conservant la procédure de retour à la ligne), veuillez définir une chaîne vide string.Empty pour HyphenSymbol.

**Returns:**
valeur String

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtient le remplissage.

**Returns:**
Valeur MarginInfo

### getPosition {#getPosition--}
```
public Position getPosition()
```

Obtient la position du paragraphe.

**Returns:**
Valeur de position

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle du paragraphe.

**Returns:**
objet Rectangle

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtient ou définit l'angle de rotation en degrés.

**Returns:**
valeur double

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Obtient la valeur du retrait des lignes suivantes.

**Returns:**
Valeur flottante

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Obtient le rectangle du texte placé dans le paragraphe.

**Returns:**
objet Rectangle

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Obtient l'alignement vertical du texte à l'intérieur du {@code Rectangle} du paragraphe. </p>

**Returns:**
Valeur VerticalAlignment @see VerticalAlignment <hr> <p> VerticalAlignment.None est égal à VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Obtient la valeur indiquant si le texte est justifié.

**Returns:**
valeur booléenne

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Définit la couleur d'arrière-plan pour le paragraphe de texte.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Définit le mode d'arrière-plan pour le paragraphe de texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur int @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Obtient ou définit la valeur du retrait des lignes suivantes. Si elle est définie sur une valeur non nulle, elle a un avantage par rapport à la valeur FormattingOptions.SubsequentLinesIndent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Définit les options de formatage.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit l'alignement horizontal du texte à l'intérieur du Rectangle du paragraphe. HorizontalAlignment.None est équivalent à HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Définit le symbole de trait d'union utilisé dans le processus de césure. Le symbole de césure est \"-\" par défaut. Pour éliminer le dessin du trait d'union (tout en conservant la procédure de retour à la ligne), veuillez définir une chaîne vide string.Empty pour HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Définit la valeur indiquant si le texte est justifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Définit le remplissage.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Définit la rotation du paragraphe.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Définit le mode de compatibilité avec l'ancien code

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Définit la position du paragraphe.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Définit le rectangle du paragraphe.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Obtient ou définit l'angle de rotation en degrés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Définit la valeur du retrait des lignes suivantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Définit l'alignement vertical du texte à l'intérieur du {@code Rectangle} du paragraphe. VerticalAlignment.None est équivalent à VerticalAlignment.Bottom.
