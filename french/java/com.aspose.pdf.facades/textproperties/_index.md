---
title: "TextProperties"
linktitle: "TextProperties"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les propriétés du texte telles que : taille du texte, couleur, style, etc."
type: docs
weight: 740
url: /fr/java/com.aspose.pdf.facades/textproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.TextProperties

```
public final class TextProperties extends Object
```

Représente les propriétés du texte telles que : taille du texte, couleur, style, etc.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextProperties](#TextProperties-double-) | Crée un objet {@code TextProperties} pour la taille de texte spécifiée |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor](#getColor--) | Obtient la couleur du texte. |
| [getTextSize](#getTextSize--) | Obtient la taille du texte. |
| [isColorSpecified](#isColorSpecified--) | Obtient une valeur indiquant si la propriété {@code Color} est spécifiée. |
| [isTextSizeSpecified](#isTextSizeSpecified--) | Obtient une valeur indiquant si la propriété {@code TextSize} est spécifiée. |
| [setColor](#setColor-java.awt.Color-) | Définit la couleur du texte. |
| [setTextSize](#setTextSize-double-) | Définit la taille du texte. |

### TextProperties {#TextProperties-double-}
```
public TextProperties(double textSize)
```

Crée un objet {@code TextProperties} pour la taille de texte spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textSize |  | Valeur de la taille du texte. |

### getColor {#getColor--}
```
public Color getColor()
```

Obtient la couleur du texte.

**Returns:**
Objet Color

### getTextSize {#getTextSize--}
```
public double getTextSize()
```

Obtient la taille du texte.

**Returns:**
valeur double

### isColorSpecified {#isColorSpecified--}
```
public boolean isColorSpecified()
```

Obtient une valeur indiquant si la propriété {@code Color} est spécifiée.

**Returns:**
valeur booléenne

### isTextSizeSpecified {#isTextSizeSpecified--}
```
public boolean isTextSizeSpecified()
```

Obtient une valeur indiquant si la propriété {@code TextSize} est spécifiée.

**Returns:**
valeur booléenne

### setColor {#setColor-java.awt.Color-}
Définit la couleur du texte.

### setTextSize {#setTextSize-double-}
```
public void setTextSize(double value)
```

Définit la taille du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |
