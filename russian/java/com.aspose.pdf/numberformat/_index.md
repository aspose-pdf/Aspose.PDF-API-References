---
title: Measure.NumberFormat
second_title: Aspose.PDF для справки по Java API
description: Числовой формат меры.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf/measure.numberformat/
---
**Наследование:**
java.lang.Object
```
public static class Measure.NumberFormat
```

Числовой формат меры.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NumberFormat(Measure measure)](#NumberFormat-com.aspose.pdf.Measure-) | Конструктор класса NumberFormat. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterText()](#getAfterText--) | Текст, который должен быть присоединен после метки |
| [getBeforeText()](#getBeforeText--) | Текст, который должен быть присоединен слева от метки. |
| [getClass()](#getClass--) |  |
| [getConvresionFactor()](#getConvresionFactor--) | Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива числового формата для получения значения в единицах этого числового формата. |
| [getDenominator()](#getDenominator--) | Если FractionDisplayment имеет значение ShowAsFraction, это значение является знаменателем дроби. |
| [getFractionDisplayment()](#getFractionDisplayment--) | Каким образом отображаются дробные значения. |
| [getFractionSeparator()](#getFractionSeparator--) | Текст, который должен использоваться в качестве десятичной позиции при отображении числовых значений. |
| [getPrecision()](#getPrecision--) | Если FractionDisplayment имеет значение ShowAsDecimal, это значение является точностью дробного значения; Оно должно быть кратно 10. |
| [getThousandsSeparator()](#getThousandsSeparator--) | Текст, который должен использоваться между порядками тысяч при отображении числовых значений. |
| [getUnitLabel()](#getUnitLabel--) | Текстовая строка, определяющая метку для отображения единиц измерения. |
| [hashCode()](#hashCode--) |  |
| [isForceDenominator()](#isForceDenominator--) | Если FractionDisplayment имеет значение ShowAsFraction, это значение определяет, будет ли уменьшаться дробь. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterText(String value)](#setAfterText-java.lang.String-) | Текст, который должен быть присоединен после метки |
| [setBeforeText(String value)](#setBeforeText-java.lang.String-) | Текст, который должен быть присоединен слева от метки. |
| [setConvresionFactor(double value)](#setConvresionFactor-double-) | Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива числового формата для получения значения в единицах этого числового формата. |
| [setDenominator(int value)](#setDenominator-int-) | Если FractionDisplayment имеет значение ShowAsFraction, это значение является знаменателем дроби. |
| [setForceDenominator(boolean value)](#setForceDenominator-boolean-) | Если FractionDisplayment имеет значение ShowAsFraction, это значение определяет, будет ли уменьшаться дробь. |
| [setFractionDisplayment(int value)](#setFractionDisplayment-int-) | Каким образом отображаются дробные значения. |
| [setFractionSeparator(String value)](#setFractionSeparator-java.lang.String-) | Текст, который должен использоваться в качестве десятичной позиции при отображении числовых значений. |
| [setPrecision(int value)](#setPrecision-int-) | Если FractionDisplayment имеет значение ShowAsDecimal, это значение является точностью дробного значения; Оно должно быть кратно 10. |
| [setThousandsSeparator(String value)](#setThousandsSeparator-java.lang.String-) | Текст, который должен использоваться между порядками тысяч при отображении числовых значений. |
| [setUnitLabel(String value)](#setUnitLabel-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NumberFormat(Measure measure) {#NumberFormat-com.aspose.pdf.Measure-}
```
public NumberFormat(Measure measure)
```


Конструктор класса NumberFormat.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| measure | [Measure](../../com.aspose.pdf/measure) | Объект меры, который содержит этот числовой формат. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getAfterText() {#getAfterText--}
```
public String getAfterText()
```


Текст, который должен быть присоединен после метки

**Возвращает:**
java.lang.String — строковый объект
### getBeforeText() {#getBeforeText--}
```
public String getBeforeText()
```


Текст, который должен быть присоединен слева от метки.

**Возвращает:**
java.lang.String — строковый объект
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getConvresionFactor() {#getConvresionFactor--}
```
public double getConvresionFactor()
```


Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива числового формата для получения значения в единицах этого числового формата.

**Возвращает:**
двойное - двойное значение
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Если FractionDisplayment имеет значение ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16.

**Возвращает:**
интервал - целочисленное значение
### getFractionDisplayment() {#getFractionDisplayment--}
```
public int getFractionDisplayment()
```


Каким образом отображаются дробные значения.

**Возвращает:**
int — значение FractionStyle
### getFractionSeparator() {#getFractionSeparator--}
```
public String getFractionSeparator()
```


Текст, который должен использоваться в качестве десятичной позиции при отображении числовых значений. Пустая строка указывает, что следует использовать значение по умолчанию. По умолчанию используется символ точки.

**Возвращает:**
java.lang.String — строковое значение
### getPrecision() {#getPrecision--}
```
public int getPrecision()
```


Если FractionDisplayment имеет значение ShowAsDecimal, это значение является точностью дробного значения; Оно должно быть кратно 10. По умолчанию 100.

**Возвращает:**
интервал - целочисленное значение
### getThousandsSeparator() {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```


Текст, который должен использоваться между порядками тысяч при отображении числовых значений. Пустая строка означает, что текст добавляться не будет. По умолчанию запятая.

**Возвращает:**
java.lang.String — строковое значение
### getUnitLabel() {#getUnitLabel--}
```
public String getUnitLabel()
```


Текстовая строка, определяющая метку для отображения единиц измерения.

**Возвращает:**
java.lang.String — строковый объект
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isForceDenominator() {#isForceDenominator--}
```
public boolean isForceDenominator()
```


Если FractionDisplayment имеет значение ShowAsFraction, это значение определяет, будет ли уменьшаться дробь. Если значение истинно, дробь не может быть уменьшена.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAfterText(String value) {#setAfterText-java.lang.String-}
```
public void setAfterText(String value)
```


Текст, который должен быть присоединен после метки

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setBeforeText(String value) {#setBeforeText-java.lang.String-}
```
public void setBeforeText(String value)
```


Текст, который должен быть присоединен слева от метки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setConvresionFactor(double value) {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```


Коэффициент преобразования, используемый для умножения значения в частичных единицах предыдущего элемента массива числового формата для получения значения в единицах этого числового формата.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setDenominator(int value) {#setDenominator-int-}
```
public void setDenominator(int value)
```


Если FractionDisplayment имеет значение ShowAsFraction, это значение является знаменателем дроби. Значение по умолчанию — 16.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setForceDenominator(boolean value) {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```


Если FractionDisplayment имеет значение ShowAsFraction, это значение определяет, будет ли уменьшаться дробь. Если значение истинно, дробь не может быть уменьшена.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFractionDisplayment(int value) {#setFractionDisplayment-int-}
```
public void setFractionDisplayment(int value)
```


Каким образом отображаются дробные значения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение FractionStyle |

### setFractionSeparator(String value) {#setFractionSeparator-java.lang.String-}
```
public void setFractionSeparator(String value)
```


Текст, который должен использоваться в качестве десятичной позиции при отображении числовых значений. Пустая строка указывает, что следует использовать значение по умолчанию. По умолчанию используется символ точки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setPrecision(int value) {#setPrecision-int-}
```
public void setPrecision(int value)
```


Если FractionDisplayment имеет значение ShowAsDecimal, это значение является точностью дробного значения; Оно должно быть кратно 10. По умолчанию 100.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setThousandsSeparator(String value) {#setThousandsSeparator-java.lang.String-}
```
public void setThousandsSeparator(String value)
```


Текст, который должен использоваться между порядками тысяч при отображении числовых значений. Пустая строка означает, что текст добавляться не будет. По умолчанию запятая.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setUnitLabel(String value) {#setUnitLabel-java.lang.String-}
```
public void setUnitLabel(String value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
