---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Aspose.PDF för Java API-referens"
description: "Talformat för mått."
type: docs
weight: 2940
url: /sv/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Talformat för mått.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Konstruktor för klassen NumberFormat. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAfterText](#getAfterText--) | Text som ska konkateneras efter etiketten |
| [getBeforeText](#getBeforeText--) | Text som ska konkateneras till vänster om etiketten. |
| [getConvresionFactor](#getConvresionFactor--) | Konversionsfaktorn som används för att multiplicera ett värde i delvisa enheter av föregående element i nummerformatarrayen för att erhålla ett värde i enheterna för detta nummerformat. |
| [getDenominator](#getDenominator--) | Om FractionDisplayment är ShowAsFraction, är detta värde nämnaren i bråket. Standardvärdet är 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | På vilket sätt bråkvärden visas. |
| [getFractionSeparator](#getFractionSeparator--) | Text som ska användas som decimaltecken vid visning av numeriska värden. En tom sträng indikerar att standardvärdet ska användas. Standard är punkttecknet. |
| [getPrecision](#getPrecision--) | Om FractionDisplayment är ShowAsDecimal, är detta värde precisionen för bråkvärdet; det ska vara en multipel av 10. Standard är 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Text som ska användas mellan tusental i visning av numeriska värden. En tom sträng indikerar att ingen text ska läggas till. Standard är komma. |
| [getUnitLabel](#getUnitLabel--) | En textsträng som specificerar en etikett för att visa enheterna. |
| [isForceDenominator](#isForceDenominator--) | Om FractionDisplayment är ShowAsFraction, bestämmer detta värde om bråket ska reduceras eller inte. Om värdet är true får bråket inte reduceras. |
| [setAfterText](#setAfterText-java.lang.String-) | Text som ska konkateneras efter etiketten |
| [setBeforeText](#setBeforeText-java.lang.String-) | Text som ska konkateneras till vänster om etiketten. |
| [setConvresionFactor](#setConvresionFactor-double-) | Konversionsfaktorn som används för att multiplicera ett värde i delvisa enheter av föregående element i nummerformatarrayen för att erhålla ett värde i enheterna för detta nummerformat. |
| [setDenominator](#setDenominator-int-) | Om FractionDisplayment är ShowAsFraction, är detta värde nämnaren i bråket. Standardvärdet är 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Om FractionDisplayment är ShowAsFraction, bestämmer detta värde om bråket ska reduceras eller inte. Om värdet är true får bråket inte reduceras. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | På vilket sätt bråkvärden visas. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Text som ska användas som decimaltecken vid visning av numeriska värden. En tom sträng indikerar att standardvärdet ska användas. Standard är punkttecknet. |
| [setPrecision](#setPrecision-int-) | Om FractionDisplayment är ShowAsDecimal, är detta värde precisionen för bråkvärdet; det ska vara en multipel av 10. Standard är 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Text som ska användas mellan tusental i visning av numeriska värden. En tom sträng indikerar att ingen text ska läggas till. Standard är komma. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Konstruktor för klassen NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Text som ska konkateneras efter etiketten

**Returns:**
String-objekt

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Text som ska konkateneras till vänster om etiketten.

**Returns:**
String-objekt

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

Konversionsfaktorn som används för att multiplicera ett värde i delvisa enheter av föregående element i nummerformatarrayen för att erhålla ett värde i enheterna för detta nummerformat.

**Returns:**
double-värde

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Om FractionDisplayment är ShowAsFraction, är detta värde nämnaren i bråket. Standardvärdet är 16.

**Returns:**
int‑värde

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

På vilket sätt bråkvärden visas.

**Returns:**
FractionStyle-värde @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Text som ska användas som decimaltecken vid visning av numeriska värden. En tom sträng indikerar att standardvärdet ska användas. Standard är punkttecknet.

**Returns:**
String värde

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Om FractionDisplayment är ShowAsDecimal, är detta värde precisionen för bråkvärdet; det ska vara en multipel av 10. Standard är 100.

**Returns:**
int‑värde

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Text som ska användas mellan tusental i visning av numeriska värden. En tom sträng indikerar att ingen text ska läggas till. Standard är komma.

**Returns:**
String värde

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

En textsträng som specificerar en etikett för att visa enheterna.

**Returns:**
String-objekt

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Om FractionDisplayment är ShowAsFraction, bestämmer detta värde om bråket ska reduceras eller inte. Om värdet är true får bråket inte reduceras.

**Returns:**
booleskt värde

### setAfterText {#setAfterText-java.lang.String-}
Text som ska konkateneras efter etiketten

### setBeforeText {#setBeforeText-java.lang.String-}
Text som ska konkateneras till vänster om etiketten.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

Konversionsfaktorn som används för att multiplicera ett värde i delvisa enheter av föregående element i nummerformatarrayen för att erhålla ett värde i enheterna för detta nummerformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Om FractionDisplayment är ShowAsFraction, är detta värde nämnaren i bråket. Standardvärdet är 16.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Om FractionDisplayment är ShowAsFraction, bestämmer detta värde om bråket ska reduceras eller inte. Om värdet är true får bråket inte reduceras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
På vilket sätt bråkvärden visas.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Text som ska användas som decimaltecken vid visning av numeriska värden. En tom sträng indikerar att standardvärdet ska användas. Standard är punkttecknet.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Om FractionDisplayment är ShowAsDecimal, är detta värde precisionen för bråkvärdet; det ska vara en multipel av 10. Standard är 100.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Text som ska användas mellan tusental i visning av numeriska värden. En tom sträng indikerar att ingen text ska läggas till. Standard är komma.

### setUnitLabel {#setUnitLabel-java.lang.String-}
