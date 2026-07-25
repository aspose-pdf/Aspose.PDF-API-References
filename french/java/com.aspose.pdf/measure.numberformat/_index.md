---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Format numérique pour la mesure."
type: docs
weight: 2940
url: /fr/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Format numérique pour la mesure.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Constructeur de la classe NumberFormat. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAfterText](#getAfterText--) | Texte qui doit être concaténé après l'étiquette |
| [getBeforeText](#getBeforeText--) | Texte qui doit être concaténé à gauche de l'étiquette. |
| [getConvresionFactor](#getConvresionFactor--) | Le facteur de conversion utilisé pour multiplier une valeur en unités partielles de l'élément précédent du tableau de formats numériques afin d'obtenir une valeur dans les unités de ce format numérique. |
| [getDenominator](#getDenominator--) | Si FractionDisplayment est ShowAsFraction, cette valeur est le dénominateur de la fraction. La valeur par défaut est 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | De quelle manière les valeurs fractionnaires sont affichées. |
| [getFractionSeparator](#getFractionSeparator--) | Texte qui doit être utilisé comme séparateur décimal lors de l'affichage des valeurs numériques. Une chaîne vide indique que la valeur par défaut doit être utilisée. La valeur par défaut est le caractère point. |
| [getPrecision](#getPrecision--) | Si FractionDisplayment est ShowAsDecimal, cette valeur est la précision de la valeur fractionnaire ; elle doit être un multiple de 10. La valeur par défaut est 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Texte qui doit être utilisé entre les ordres de mille lors de l'affichage des valeurs numériques. Une chaîne vide indique qu'aucun texte ne doit être ajouté. La valeur par défaut est la virgule. |
| [getUnitLabel](#getUnitLabel--) | Une chaîne de texte spécifiant une étiquette pour l'affichage des unités. |
| [isForceDenominator](#isForceDenominator--) | Si FractionDisplayment est ShowAsFraction, cette valeur détermine si la fraction doit être réduite ou non. Si la valeur est vraie, la fraction ne sera pas réduite. |
| [setAfterText](#setAfterText-java.lang.String-) | Texte qui doit être concaténé après l'étiquette |
| [setBeforeText](#setBeforeText-java.lang.String-) | Texte qui doit être concaténé à gauche de l'étiquette. |
| [setConvresionFactor](#setConvresionFactor-double-) | Le facteur de conversion utilisé pour multiplier une valeur en unités partielles de l'élément précédent du tableau de formats numériques afin d'obtenir une valeur dans les unités de ce format numérique. |
| [setDenominator](#setDenominator-int-) | Si FractionDisplayment est ShowAsFraction, cette valeur est le dénominateur de la fraction. La valeur par défaut est 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Si FractionDisplayment est ShowAsFraction, cette valeur détermine si la fraction doit être réduite ou non. Si la valeur est vraie, la fraction ne sera pas réduite. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | De quelle manière les valeurs fractionnaires sont affichées. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Texte qui doit être utilisé comme séparateur décimal lors de l'affichage des valeurs numériques. Une chaîne vide indique que la valeur par défaut doit être utilisée. La valeur par défaut est le caractère point. |
| [setPrecision](#setPrecision-int-) | Si FractionDisplayment est ShowAsDecimal, cette valeur est la précision de la valeur fractionnaire ; elle doit être un multiple de 10. La valeur par défaut est 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Texte qui doit être utilisé entre les ordres de mille lors de l'affichage des valeurs numériques. Une chaîne vide indique qu'aucun texte ne doit être ajouté. La valeur par défaut est la virgule. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Constructeur de la classe NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Texte qui doit être concaténé après l'étiquette

**Returns:**
Objet String

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Texte qui doit être concaténé à gauche de l'étiquette.

**Returns:**
Objet String

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

Le facteur de conversion utilisé pour multiplier une valeur en unités partielles de l'élément précédent du tableau de formats numériques afin d'obtenir une valeur dans les unités de ce format numérique.

**Returns:**
valeur double

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Si FractionDisplayment est ShowAsFraction, cette valeur est le dénominateur de la fraction. La valeur par défaut est 16.

**Returns:**
valeur int

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

De quelle manière les valeurs fractionnaires sont affichées.

**Returns:**
Valeur FractionStyle @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Texte qui doit être utilisé comme séparateur décimal lors de l'affichage des valeurs numériques. Une chaîne vide indique que la valeur par défaut doit être utilisée. La valeur par défaut est le caractère point.

**Returns:**
valeur String

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Si FractionDisplayment est ShowAsDecimal, cette valeur est la précision de la valeur fractionnaire ; elle doit être un multiple de 10. La valeur par défaut est 100.

**Returns:**
valeur int

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Texte qui doit être utilisé entre les ordres de mille lors de l'affichage des valeurs numériques. Une chaîne vide indique qu'aucun texte ne doit être ajouté. La valeur par défaut est la virgule.

**Returns:**
valeur String

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

Une chaîne de texte spécifiant une étiquette pour l'affichage des unités.

**Returns:**
Objet String

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Si FractionDisplayment est ShowAsFraction, cette valeur détermine si la fraction doit être réduite ou non. Si la valeur est vraie, la fraction ne sera pas réduite.

**Returns:**
valeur booléenne

### setAfterText {#setAfterText-java.lang.String-}
Texte qui doit être concaténé après l'étiquette

### setBeforeText {#setBeforeText-java.lang.String-}
Texte qui doit être concaténé à gauche de l'étiquette.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

Le facteur de conversion utilisé pour multiplier une valeur en unités partielles de l'élément précédent du tableau de formats numériques afin d'obtenir une valeur dans les unités de ce format numérique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Si FractionDisplayment est ShowAsFraction, cette valeur est le dénominateur de la fraction. La valeur par défaut est 16.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Si FractionDisplayment est ShowAsFraction, cette valeur détermine si la fraction doit être réduite ou non. Si la valeur est vraie, la fraction ne sera pas réduite.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
De quelle manière les valeurs fractionnaires sont affichées.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Texte qui doit être utilisé comme séparateur décimal lors de l'affichage des valeurs numériques. Une chaîne vide indique que la valeur par défaut doit être utilisée. La valeur par défaut est le caractère point.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Si FractionDisplayment est ShowAsDecimal, cette valeur est la précision de la valeur fractionnaire ; elle doit être un multiple de 10. La valeur par défaut est 100.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Texte qui doit être utilisé entre les ordres de mille lors de l'affichage des valeurs numériques. Une chaîne vide indique qu'aucun texte ne doit être ajouté. La valeur par défaut est la virgule.

### setUnitLabel {#setUnitLabel-java.lang.String-}
