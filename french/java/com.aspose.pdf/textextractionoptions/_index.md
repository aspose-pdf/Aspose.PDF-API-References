---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options d'extraction de texte"
type: docs
weight: 5060
url: /fr/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Représente les options d'extraction de texte

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Initialise une nouvelle instance de l'objet {@code TextExtractionOptions} pour le mode de formatage de texte spécifié. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Obtient le mode de formatage. |
| [getScaleFactor](#getScaleFactor--) | Obtient le facteur qui sera appliqué pour mettre à l'échelle la taille de la police lors de l'extraction en mode pur. Une valeur plus faible entraîne davantage d'espaces dans le texte extrait. La valeur par défaut est 1 - aucune mise à l'échelle ; définir la valeur à zéro permet à l'algorithme de choisir automatiquement l'échelle. |
| [setFormattingMode](#setFormattingMode-int-) | Définit le mode de formatage. |
| [setScaleFactor](#setScaleFactor-double-) | Définit le facteur qui sera appliqué pour mettre à l'échelle la taille de la police lors de l'extraction en mode pur. Une valeur plus faible entraîne davantage d'espaces dans le texte extrait (de 1 à 10). La valeur par défaut est 1 - aucune mise à l'échelle ; définir la valeur à zéro permet à l'algorithme de choisir automatiquement l'échelle. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Initialise une nouvelle instance de l'objet {@code TextExtractionOptions} pour le mode de formatage de texte spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| formattingMode |  | Valeur du mode de formatage du texte. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Obtient le mode de formatage.

**Returns:**
TextFormattingMode valeur @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Obtient le facteur qui sera appliqué pour mettre à l'échelle la taille de la police lors de l'extraction en mode pur. Une valeur plus faible entraîne davantage d'espaces dans le texte extrait. La valeur par défaut est 1 - aucune mise à l'échelle ; définir la valeur à zéro permet à l'algorithme de choisir automatiquement l'échelle.

**Returns:**
valeur double

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Définit le mode de formatage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | TextFormattingMode valeur @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Définit le facteur qui sera appliqué pour mettre à l'échelle la taille de la police lors de l'extraction en mode pur. Une valeur plus faible entraîne davantage d'espaces dans le texte extrait (de 1 à 10). La valeur par défaut est 1 - aucune mise à l'échelle ; définir la valeur à zéro permet à l'algorithme de choisir automatiquement l'échelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |
