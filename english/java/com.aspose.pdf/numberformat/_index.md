---
title: Measure.NumberFormat
second_title: Aspose.PDF for Java API Reference
description: Number format for measure.
type: docs
weight: 10
url: /java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object
```
public static class Measure.NumberFormat
```

Number format for measure.
## Constructors

| Constructor | Description |
| --- | --- |
| [NumberFormat(Measure measure)](#NumberFormat-com.aspose.pdf.Measure-) | Constructor for NumberFormat class. |
## Methods

| Method | Description |
| --- | --- |
| [getUnitLabel()](#getUnitLabel--) | A text string specifying a label for displaying the units. |
| [setUnitLabel(String value)](#setUnitLabel-java.lang.String-) |  |
| [getConvresionFactor()](#getConvresionFactor--) | The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format. |
| [setConvresionFactor(double value)](#setConvresionFactor-double-) | The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format. |
| [getFractionDisplayment()](#getFractionDisplayment--) | In what manner fractional values are displayed. |
| [setFractionDisplayment(int value)](#setFractionDisplayment-int-) | In what manner fractional values are displayed. |
| [getPrecision()](#getPrecision--) | If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. |
| [setPrecision(int value)](#setPrecision-int-) | If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. |
| [getDenominator()](#getDenominator--) | If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. |
| [setDenominator(int value)](#setDenominator-int-) | If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. |
| [isForceDenominator()](#isForceDenominator--) | If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. |
| [setForceDenominator(boolean value)](#setForceDenominator-boolean-) | If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. |
| [getThousandsSeparator()](#getThousandsSeparator--) | Text that shall be used between orders of thousands in display of numerical values. |
| [setThousandsSeparator(String value)](#setThousandsSeparator-java.lang.String-) | Text that shall be used between orders of thousands in display of numerical values. |
| [getFractionSeparator()](#getFractionSeparator--) | Text that shall be used as the decimal position in displaying numerical values. |
| [setFractionSeparator(String value)](#setFractionSeparator-java.lang.String-) | Text that shall be used as the decimal position in displaying numerical values. |
| [getBeforeText()](#getBeforeText--) | Text that shall be concatenated to the left of the label. |
| [setBeforeText(String value)](#setBeforeText-java.lang.String-) | Text that shall be concatenated to the left of the label. |
| [getAfterText()](#getAfterText--) | Text that shall be concatenated after the label |
| [setAfterText(String value)](#setAfterText-java.lang.String-) | Text that shall be concatenated after the label |
### NumberFormat(Measure measure) {#NumberFormat-com.aspose.pdf.Measure-}
```
public NumberFormat(Measure measure)
```


Constructor for NumberFormat class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| measure | [Measure](../../com.aspose.pdf/measure) | Measure object which contains this number format. |

### getUnitLabel() {#getUnitLabel--}
```
public String getUnitLabel()
```


A text string specifying a label for displaying the units.

**Returns:**
java.lang.String - String object
### setUnitLabel(String value) {#setUnitLabel-java.lang.String-}
```
public void setUnitLabel(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getConvresionFactor() {#getConvresionFactor--}
```
public double getConvresionFactor()
```


The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format.

**Returns:**
double - double value
### setConvresionFactor(double value) {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```


The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getFractionDisplayment() {#getFractionDisplayment--}
```
public int getFractionDisplayment()
```


In what manner fractional values are displayed.

**Returns:**
int - FractionStyle value
### setFractionDisplayment(int value) {#setFractionDisplayment-int-}
```
public void setFractionDisplayment(int value)
```


In what manner fractional values are displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FractionStyle value |

### getPrecision() {#getPrecision--}
```
public int getPrecision()
```


If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100.

**Returns:**
int - int value
### setPrecision(int value) {#setPrecision-int-}
```
public void setPrecision(int value)
```


If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16.

**Returns:**
int - int value
### setDenominator(int value) {#setDenominator-int-}
```
public void setDenominator(int value)
```


If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### isForceDenominator() {#isForceDenominator--}
```
public boolean isForceDenominator()
```


If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced.

**Returns:**
boolean - boolean value
### setForceDenominator(boolean value) {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```


If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getThousandsSeparator() {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```


Text that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma.

**Returns:**
java.lang.String - String value
### setThousandsSeparator(String value) {#setThousandsSeparator-java.lang.String-}
```
public void setThousandsSeparator(String value)
```


Text that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFractionSeparator() {#getFractionSeparator--}
```
public String getFractionSeparator()
```


Text that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character.

**Returns:**
java.lang.String - String value
### setFractionSeparator(String value) {#setFractionSeparator-java.lang.String-}
```
public void setFractionSeparator(String value)
```


Text that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getBeforeText() {#getBeforeText--}
```
public String getBeforeText()
```


Text that shall be concatenated to the left of the label.

**Returns:**
java.lang.String - String object
### setBeforeText(String value) {#setBeforeText-java.lang.String-}
```
public void setBeforeText(String value)
```


Text that shall be concatenated to the left of the label.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getAfterText() {#getAfterText--}
```
public String getAfterText()
```


Text that shall be concatenated after the label

**Returns:**
java.lang.String - String object
### setAfterText(String value) {#setAfterText-java.lang.String-}
```
public void setAfterText(String value)
```


Text that shall be concatenated after the label

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

