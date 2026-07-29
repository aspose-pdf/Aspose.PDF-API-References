---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de mise en forme du texte"
type: docs
weight: 5080
url: /fr/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Représente les options de mise en forme du texte

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Initialise une nouvelle instance de l'objet {@code TextFormattingOptions} avec un mode de retour à la ligne indéfini. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Initialise une nouvelle instance de l'objet {@code TextFormattingOptions} pour le mode de retour à la ligne spécifié. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Obtient ou définit la valeur du retrait de la première ligne. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Obtient ou définit le symbole de trait d'union utilisé dans le processus de césure. </p><hr> Pour éliminer le dessin du trait d'union (tout en conservant la procédure d'enroulement) veuillez définir une chaîne vide string.Empty pour HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | Obtient le mode d'espacement des lignes. La valeur par défaut est LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Obtient ou définit la valeur d'indentation des lignes suivantes. |
| [getWrapMode](#getWrapMode--) | Obtient le mode de retour à la ligne. La valeur par défaut est WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Obtient ou définit la valeur du retrait de la première ligne. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Obtient ou définit le symbole de trait d'union utilisé dans le processus de césure. </p><hr> Pour éliminer le dessin du trait d'union (tout en conservant la procédure d'enroulement) veuillez définir une chaîne vide string.Empty pour HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | Définit le mode d'espacement des lignes. La valeur par défaut est LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Obtient ou définit la valeur d'indentation des lignes suivantes. |
| [setWrapMode](#setWrapMode-int-) | Définit le mode de retour à la ligne. La valeur par défaut est WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Initialise une nouvelle instance de l'objet {@code TextFormattingOptions} avec un mode de retour à la ligne indéfini.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Initialise une nouvelle instance de l'objet {@code TextFormattingOptions} pour le mode de retour à la ligne spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| wrapMode |  | Mode de retour à la ligne. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Obtient ou définit la valeur du retrait de la première ligne.

**Returns:**
Valeur flottante

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Obtient ou définit le symbole de trait d'union utilisé dans le processus de césure. </p><hr> Pour éliminer le dessin du trait d'union (tout en conservant la procédure d'enroulement) veuillez définir une chaîne vide string.Empty pour HyphenSymbol.

**Returns:**
valeur String

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Obtient le mode d'espacement des lignes. La valeur par défaut est LineSpacingMode.FontSize

**Returns:**
valeur int @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Obtient ou définit la valeur d'indentation des lignes suivantes.

**Returns:**
Valeur flottante

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Obtient le mode de retour à la ligne. La valeur par défaut est WordWrapMode.NoWrap

**Returns:**
valeur WordWrapMode @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Obtient ou définit la valeur du retrait de la première ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Obtient ou définit le symbole de trait d'union utilisé dans le processus de césure. </p><hr> Pour éliminer le dessin du trait d'union (tout en conservant la procédure d'enroulement) veuillez définir une chaîne vide string.Empty pour HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Définit le mode d'espacement des lignes. La valeur par défaut est LineSpacingMode.FontSize

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Obtient ou définit la valeur d'indentation des lignes suivantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Définit le mode de retour à la ligne. La valeur par défaut est WordWrapMode.NoWrap

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur WordWrapMode @see WordWrapMode |
