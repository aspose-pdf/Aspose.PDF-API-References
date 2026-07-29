---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Справочник API Aspose.PDF для Java"
description: "Формат числа для измерения."
type: docs
weight: 2940
url: /ru/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Формат числа для измерения.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Конструктор класса NumberFormat. |

## Методы

| Метод | Описание |
| --- | --- |
| [getAfterText](#getAfterText--) | Текст, который будет добавлен после метки. |
| [getBeforeText](#getBeforeText--) | Текст, который будет добавлен слева от метки. |
| [getConvresionFactor](#getConvresionFactor--) | Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива форматов чисел, чтобы получить значение в единицах текущего формата числа. |
| [getDenominator](#getDenominator--) | Если FractionDisplayment установлен в ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | Способ отображения дробных значений. |
| [getFractionSeparator](#getFractionSeparator--) | Текст, который будет использоваться в качестве десятичного разделителя при отображении числовых значений. Пустая строка указывает на использование значения по умолчанию. По умолчанию — точка. |
| [getPrecision](#getPrecision--) | Если FractionDisplayment установлен в ShowAsDecimal, это значение определяет точность дробного значения; оно должно быть кратным 10. Значение по умолчанию — 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Текст, который будет использоваться между разрядами тысяч при отображении числовых значений. Пустая строка указывает, что текст не будет добавлен. По умолчанию — запятая. |
| [getUnitLabel](#getUnitLabel--) | Текстовая строка, задающая метку для отображения единиц измерения. |
| [isForceDenominator](#isForceDenominator--) | Если FractionDisplayment установлен в ShowAsFraction, это значение определяет, следует ли сокращать дробь. Если значение истинно, дробь может не сокращаться. |
| [setAfterText](#setAfterText-java.lang.String-) | Текст, который будет добавлен после метки. |
| [setBeforeText](#setBeforeText-java.lang.String-) | Текст, который будет добавлен слева от метки. |
| [setConvresionFactor](#setConvresionFactor-double-) | Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива форматов чисел, чтобы получить значение в единицах текущего формата числа. |
| [setDenominator](#setDenominator-int-) | Если FractionDisplayment установлен в ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Если FractionDisplayment установлен в ShowAsFraction, это значение определяет, следует ли сокращать дробь. Если значение истинно, дробь может не сокращаться. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | Способ отображения дробных значений. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Текст, который будет использоваться в качестве десятичного разделителя при отображении числовых значений. Пустая строка указывает на использование значения по умолчанию. По умолчанию — точка. |
| [setPrecision](#setPrecision-int-) | Если FractionDisplayment установлен в ShowAsDecimal, это значение определяет точность дробного значения; оно должно быть кратным 10. Значение по умолчанию — 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Текст, который будет использоваться между разрядами тысяч при отображении числовых значений. Пустая строка указывает, что текст не будет добавлен. По умолчанию — запятая. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Конструктор класса NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Текст, который будет добавлен после метки.

**Returns:**
String объект

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Текст, который будет добавлен слева от метки.

**Returns:**
String объект

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива форматов чисел, чтобы получить значение в единицах текущего формата числа.

**Returns:**
double значение

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Если FractionDisplayment установлен в ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16.

**Returns:**
int значение

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

Способ отображения дробных значений.

**Returns:**
FractionStyle значение @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Текст, который будет использоваться в качестве десятичного разделителя при отображении числовых значений. Пустая строка указывает на использование значения по умолчанию. По умолчанию — точка.

**Returns:**
строковое значение

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Если FractionDisplayment установлен в ShowAsDecimal, это значение определяет точность дробного значения; оно должно быть кратным 10. Значение по умолчанию — 100.

**Returns:**
int значение

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Текст, который будет использоваться между разрядами тысяч при отображении числовых значений. Пустая строка указывает, что текст не будет добавлен. По умолчанию — запятая.

**Returns:**
строковое значение

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

Текстовая строка, задающая метку для отображения единиц измерения.

**Returns:**
String объект

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Если FractionDisplayment установлен в ShowAsFraction, это значение определяет, следует ли сокращать дробь. Если значение истинно, дробь может не сокращаться.

**Returns:**
логическое значение

### setAfterText {#setAfterText-java.lang.String-}
Текст, который будет добавлен после метки.

### setBeforeText {#setBeforeText-java.lang.String-}
Текст, который будет добавлен слева от метки.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива форматов чисел, чтобы получить значение в единицах текущего формата числа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | double значение |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Если FractionDisplayment установлен в ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Если FractionDisplayment установлен в ShowAsFraction, это значение определяет, следует ли сокращать дробь. Если значение истинно, дробь может не сокращаться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
Способ отображения дробных значений.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Текст, который будет использоваться в качестве десятичного разделителя при отображении числовых значений. Пустая строка указывает на использование значения по умолчанию. По умолчанию — точка.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Если FractionDisplayment установлен в ShowAsDecimal, это значение определяет точность дробного значения; оно должно быть кратным 10. Значение по умолчанию — 100.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | int значение |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Текст, который будет использоваться между разрядами тысяч при отображении числовых значений. Пустая строка указывает, что текст не будет добавлен. По умолчанию — запятая.

### setUnitLabel {#setUnitLabel-java.lang.String-}
