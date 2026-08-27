---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Formato numerico per la misura."
type: docs
weight: 2940
url: /it/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Formato numerico per la misura.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Costruttore per la classe NumberFormat. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAfterText](#getAfterText--) | Testo da concatenare dopo l'etichetta |
| [getBeforeText](#getBeforeText--) | Testo da concatenare a sinistra dell'etichetta. |
| [getConvresionFactor](#getConvresionFactor--) | Il fattore di conversione usato per moltiplicare un valore in unità parziali dell'elemento precedente dell'array di formati numerici per ottenere un valore nelle unità di questo formato numerico. |
| [getDenominator](#getDenominator--) | Se FractionDisplayment è ShowAsFraction, questo valore è il denominatore della frazione. Il valore predefinito è 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | In che modo i valori frazionari vengono visualizzati. |
| [getFractionSeparator](#getFractionSeparator--) | Testo da utilizzare come posizione decimale nella visualizzazione dei valori numerici. Una stringa vuota indica che verrà usato il valore predefinito. Il valore predefinito è il punto. |
| [getPrecision](#getPrecision--) | Se FractionDisplayment è ShowAsDecimal, questo valore è la precisione del valore frazionario; deve essere un multiplo di 10. Il valore predefinito è 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Testo da utilizzare tra le migliaia nella visualizzazione dei valori numerici. Una stringa vuota indica che non verrà aggiunto alcun testo. Il valore predefinito è la virgola. |
| [getUnitLabel](#getUnitLabel--) | Una stringa di testo che specifica un'etichetta per visualizzare le unità. |
| [isForceDenominator](#isForceDenominator--) | Se FractionDisplayment è ShowAsFraction, questo valore determina se la frazione debba essere ridotta o meno. Se il valore è true la frazione non può essere ridotta. |
| [setAfterText](#setAfterText-java.lang.String-) | Testo da concatenare dopo l'etichetta |
| [setBeforeText](#setBeforeText-java.lang.String-) | Testo da concatenare a sinistra dell'etichetta. |
| [setConvresionFactor](#setConvresionFactor-double-) | Il fattore di conversione usato per moltiplicare un valore in unità parziali dell'elemento precedente dell'array di formati numerici per ottenere un valore nelle unità di questo formato numerico. |
| [setDenominator](#setDenominator-int-) | Se FractionDisplayment è ShowAsFraction, questo valore è il denominatore della frazione. Il valore predefinito è 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Se FractionDisplayment è ShowAsFraction, questo valore determina se la frazione debba essere ridotta o meno. Se il valore è true la frazione non può essere ridotta. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | In che modo i valori frazionari vengono visualizzati. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Testo da utilizzare come posizione decimale nella visualizzazione dei valori numerici. Una stringa vuota indica che verrà usato il valore predefinito. Il valore predefinito è il punto. |
| [setPrecision](#setPrecision-int-) | Se FractionDisplayment è ShowAsDecimal, questo valore è la precisione del valore frazionario; deve essere un multiplo di 10. Il valore predefinito è 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Testo da utilizzare tra le migliaia nella visualizzazione dei valori numerici. Una stringa vuota indica che non verrà aggiunto alcun testo. Il valore predefinito è la virgola. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Costruttore per la classe NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Testo da concatenare dopo l'etichetta

**Returns:**
Oggetto stringa

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Testo da concatenare a sinistra dell'etichetta.

**Returns:**
Oggetto stringa

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

Il fattore di conversione usato per moltiplicare un valore in unità parziali dell'elemento precedente dell'array di formati numerici per ottenere un valore nelle unità di questo formato numerico.

**Returns:**
valore double

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Se FractionDisplayment è ShowAsFraction, questo valore è il denominatore della frazione. Il valore predefinito è 16.

**Returns:**
valore int

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

In che modo i valori frazionari vengono visualizzati.

**Returns:**
Valore FractionStyle @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Testo da utilizzare come posizione decimale nella visualizzazione dei valori numerici. Una stringa vuota indica che verrà usato il valore predefinito. Il valore predefinito è il punto.

**Returns:**
valore String

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Se FractionDisplayment è ShowAsDecimal, questo valore è la precisione del valore frazionario; deve essere un multiplo di 10. Il valore predefinito è 100.

**Returns:**
valore int

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Testo da utilizzare tra le migliaia nella visualizzazione dei valori numerici. Una stringa vuota indica che non verrà aggiunto alcun testo. Il valore predefinito è la virgola.

**Returns:**
valore String

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

Una stringa di testo che specifica un'etichetta per visualizzare le unità.

**Returns:**
Oggetto stringa

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Se FractionDisplayment è ShowAsFraction, questo valore determina se la frazione debba essere ridotta o meno. Se il valore è true la frazione non può essere ridotta.

**Returns:**
valore booleano

### setAfterText {#setAfterText-java.lang.String-}
Testo da concatenare dopo l'etichetta

### setBeforeText {#setBeforeText-java.lang.String-}
Testo da concatenare a sinistra dell'etichetta.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

Il fattore di conversione usato per moltiplicare un valore in unità parziali dell'elemento precedente dell'array di formati numerici per ottenere un valore nelle unità di questo formato numerico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Se FractionDisplayment è ShowAsFraction, questo valore è il denominatore della frazione. Il valore predefinito è 16.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Se FractionDisplayment è ShowAsFraction, questo valore determina se la frazione debba essere ridotta o meno. Se il valore è true la frazione non può essere ridotta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
In che modo i valori frazionari vengono visualizzati.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Testo da utilizzare come posizione decimale nella visualizzazione dei valori numerici. Una stringa vuota indica che verrà usato il valore predefinito. Il valore predefinito è il punto.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Se FractionDisplayment è ShowAsDecimal, questo valore è la precisione del valore frazionario; deve essere un multiplo di 10. Il valore predefinito è 100.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Testo da utilizzare tra le migliaia nella visualizzazione dei valori numerici. Una stringa vuota indica che non verrà aggiunto alcun testo. Il valore predefinito è la virgola.

### setUnitLabel {#setUnitLabel-java.lang.String-}
