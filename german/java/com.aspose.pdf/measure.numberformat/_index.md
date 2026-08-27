---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Zahlenformat für Measure."
type: docs
weight: 2940
url: /de/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Zahlenformat für Measure.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Konstruktor für die Klasse NumberFormat. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAfterText](#getAfterText--) | Text, der nach dem Etikett angehängt werden soll |
| [getBeforeText](#getBeforeText--) | Text, der links vom Etikett angehängt werden soll. |
| [getConvresionFactor](#getConvresionFactor--) | Der Umrechnungsfaktor, der verwendet wird, um einen Wert in Teil‑einheiten des vorherigen Elements des Zahlenformat‑Arrays zu multiplizieren, um einen Wert in den Einheiten dieses Zahlenformats zu erhalten. |
| [getDenominator](#getDenominator--) | Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, ist dieser Wert der Nenner des Bruchs. Der Standardwert ist 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | Auf welche Weise Bruchwerte angezeigt werden. |
| [getFractionSeparator](#getFractionSeparator--) | Text, der als Dezimaltrennzeichen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass der Standard verwendet wird. Standard ist das Punktzeichen. |
| [getPrecision](#getPrecision--) | Wenn FractionDisplayment auf ShowAsDecimal eingestellt ist, ist dieser Wert die Genauigkeit des Bruchwertes; er muss ein Vielfaches von 10 sein. Standard ist 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Text, der zwischen Tausendergruppen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass kein Text hinzugefügt wird. Standard ist das Komma. |
| [getUnitLabel](#getUnitLabel--) | Eine Textzeichenfolge, die ein Etikett für die Anzeige der Einheiten angibt. |
| [isForceDenominator](#isForceDenominator--) | Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, bestimmt dieser Wert, ob der Bruch reduziert werden darf oder nicht. Wenn der Wert true ist, darf der Bruch nicht reduziert werden. |
| [setAfterText](#setAfterText-java.lang.String-) | Text, der nach dem Etikett angehängt werden soll |
| [setBeforeText](#setBeforeText-java.lang.String-) | Text, der links vom Etikett angehängt werden soll. |
| [setConvresionFactor](#setConvresionFactor-double-) | Der Umrechnungsfaktor, der verwendet wird, um einen Wert in Teil‑einheiten des vorherigen Elements des Zahlenformat‑Arrays zu multiplizieren, um einen Wert in den Einheiten dieses Zahlenformats zu erhalten. |
| [setDenominator](#setDenominator-int-) | Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, ist dieser Wert der Nenner des Bruchs. Der Standardwert ist 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, bestimmt dieser Wert, ob der Bruch reduziert werden darf oder nicht. Wenn der Wert true ist, darf der Bruch nicht reduziert werden. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | Auf welche Weise Bruchwerte angezeigt werden. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Text, der als Dezimaltrennzeichen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass der Standard verwendet wird. Standard ist das Punktzeichen. |
| [setPrecision](#setPrecision-int-) | Wenn FractionDisplayment auf ShowAsDecimal eingestellt ist, ist dieser Wert die Genauigkeit des Bruchwertes; er muss ein Vielfaches von 10 sein. Standard ist 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Text, der zwischen Tausendergruppen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass kein Text hinzugefügt wird. Standard ist das Komma. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Konstruktor für die Klasse NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Text, der nach dem Etikett angehängt werden soll

**Returns:**
String-Objekt

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Text, der links vom Etikett angehängt werden soll.

**Returns:**
String-Objekt

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

Der Umrechnungsfaktor, der verwendet wird, um einen Wert in Teil‑einheiten des vorherigen Elements des Zahlenformat‑Arrays zu multiplizieren, um einen Wert in den Einheiten dieses Zahlenformats zu erhalten.

**Returns:**
double-Wert

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, ist dieser Wert der Nenner des Bruchs. Der Standardwert ist 16.

**Returns:**
int-Wert

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

Auf welche Weise Bruchwerte angezeigt werden.

**Returns:**
FractionStyle-Wert @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Text, der als Dezimaltrennzeichen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass der Standard verwendet wird. Standard ist das Punktzeichen.

**Returns:**
String Wert

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Wenn FractionDisplayment auf ShowAsDecimal eingestellt ist, ist dieser Wert die Genauigkeit des Bruchwertes; er muss ein Vielfaches von 10 sein. Standard ist 100.

**Returns:**
int-Wert

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Text, der zwischen Tausendergruppen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass kein Text hinzugefügt wird. Standard ist das Komma.

**Returns:**
String Wert

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

Eine Textzeichenfolge, die ein Etikett für die Anzeige der Einheiten angibt.

**Returns:**
String-Objekt

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, bestimmt dieser Wert, ob der Bruch reduziert werden darf oder nicht. Wenn der Wert true ist, darf der Bruch nicht reduziert werden.

**Returns:**
boolescher Wert

### setAfterText {#setAfterText-java.lang.String-}
Text, der nach dem Etikett angehängt werden soll

### setBeforeText {#setBeforeText-java.lang.String-}
Text, der links vom Etikett angehängt werden soll.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

Der Umrechnungsfaktor, der verwendet wird, um einen Wert in Teil‑einheiten des vorherigen Elements des Zahlenformat‑Arrays zu multiplizieren, um einen Wert in den Einheiten dieses Zahlenformats zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, ist dieser Wert der Nenner des Bruchs. Der Standardwert ist 16.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Wenn FractionDisplayment auf ShowAsFraction eingestellt ist, bestimmt dieser Wert, ob der Bruch reduziert werden darf oder nicht. Wenn der Wert true ist, darf der Bruch nicht reduziert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
Auf welche Weise Bruchwerte angezeigt werden.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Text, der als Dezimaltrennzeichen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass der Standard verwendet wird. Standard ist das Punktzeichen.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Wenn FractionDisplayment auf ShowAsDecimal eingestellt ist, ist dieser Wert die Genauigkeit des Bruchwertes; er muss ein Vielfaches von 10 sein. Standard ist 100.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Text, der zwischen Tausendergruppen bei der Anzeige numerischer Werte verwendet werden soll. Ein leerer String bedeutet, dass kein Text hinzugefügt wird. Standard ist das Komma.

### setUnitLabel {#setUnitLabel-java.lang.String-}
