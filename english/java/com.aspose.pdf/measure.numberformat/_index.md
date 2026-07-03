---
title: Measure.NumberFormat
second_title: Aspose.PDF for Java API Reference
description: Number format for measure.
type: docs
weight: 2940
url: /java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Number format for measure.

## Constructors

| Constructor | Description |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Constructor for NumberFormat class. |

## Methods

| Method | Description |
| --- | --- |
| [getAfterText](#getAfterText--) | Text that shall be concatenated after the label |
| [getBeforeText](#getBeforeText--) | Text that shall be concatenated to the left of the label. |
| [getConvresionFactor](#getConvresionFactor--) | The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format. |
| [getDenominator](#getDenominator--) | If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | In what manner fractional values are displayed. |
| [getFractionSeparator](#getFractionSeparator--) | Text that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character. |
| [getPrecision](#getPrecision--) | If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Text that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma. |
| [getUnitLabel](#getUnitLabel--) | A text string specifying a label for displaying the units. |
| [isForceDenominator](#isForceDenominator--) | If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced. |
| [setAfterText](#setAfterText-java.lang.String-) | Text that shall be concatenated after the label |
| [setBeforeText](#setBeforeText-java.lang.String-) | Text that shall be concatenated to the left of the label. |
| [setConvresionFactor](#setConvresionFactor-double-) | The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format. |
| [setDenominator](#setDenominator-int-) | If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | In what manner fractional values are displayed. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Text that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character. |
| [setPrecision](#setPrecision-int-) | If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Text that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Constructor for NumberFormat class.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Text that shall be concatenated after the label

**Returns:**
String object

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Text that shall be concatenated to the left of the label.

**Returns:**
String object

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format.

**Returns:**
double value

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16.

**Returns:**
int value

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

In what manner fractional values are displayed.

**Returns:**
FractionStyle value @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Text that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character.

**Returns:**
String value

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100.

**Returns:**
int value

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Text that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma.

**Returns:**
String value

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

A text string specifying a label for displaying the units.

**Returns:**
String object

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced.

**Returns:**
boolean value

### setAfterText {#setAfterText-java.lang.String-}
Text that shall be concatenated after the label

### setBeforeText {#setBeforeText-java.lang.String-}
Text that shall be concatenated to the left of the label.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

The conversion factor used to multiply a value in partial units of the previous number format array element to obtain a value in the units of this number format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

If FractionDisplayment is ShowAsFraction, this value is denominator of the fraction. Default value is 16.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

If FractionDisplayment is ShowAsFraction, this value determines meay or not the fraction be reduced. If value is true fraction may not be reduced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
In what manner fractional values are displayed.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Text that shall be used as the decimal position in displaying numerical values. An empty string indicates that the default shall be used. Default is period character.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

If FractionDisplayment is ShowAsDecimal, this value is precision of fractional value; It shall me multiple of 10. Default is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Text that shall be used between orders of thousands in display of numerical values. An empty string indicates that no text shall be added. Default is comma.

### setUnitLabel {#setUnitLabel-java.lang.String-}
