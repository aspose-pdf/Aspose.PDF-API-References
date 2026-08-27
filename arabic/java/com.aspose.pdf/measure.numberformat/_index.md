---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تنسيق الرقم للقياس."
type: docs
weight: 2940
url: /ar/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

تنسيق الرقم للقياس.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | منشئ لفئة NumberFormat. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAfterText](#getAfterText--) | النص الذي سيُضمّن بعد التسمية |
| [getBeforeText](#getBeforeText--) | النص الذي سيُضمّن إلى يسار التسمية. |
| [getConvresionFactor](#getConvresionFactor--) | عامل التحويل المستخدم لضرب قيمة بوحدات جزئية من العنصر السابق في مصفوفة تنسيق الأرقام للحصول على قيمة بوحدات تنسيق الأرقام هذا. |
| [getDenominator](#getDenominator--) | إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة هي مقام الكسر. القيمة الافتراضية هي 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | بالطريقة التي يتم بها عرض القيم الكسرية. |
| [getFractionSeparator](#getFractionSeparator--) | النص الذي سيُستخدم كموقع عشري عند عرض القيم العددية. سلسلة فارغة تشير إلى أنه سيتم استخدام القيمة الافتراضية. القيمة الافتراضية هي حرف النقطة. |
| [getPrecision](#getPrecision--) | إذا كان FractionDisplayment هو ShowAsDecimal، فإن هذه القيمة هي دقة القيمة الكسرية؛ يجب أن تكون مضاعفًا للعدد 10. القيمة الافتراضية هي 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | النص الذي سيُستخدم بين فئات الآلاف عند عرض القيم العددية. سلسلة فارغة تشير إلى عدم إضافة أي نص. القيمة الافتراضية هي الفاصلة. |
| [getUnitLabel](#getUnitLabel--) | سلسلة نصية تحدد تسمية لعرض الوحدات. |
| [isForceDenominator](#isForceDenominator--) | إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة تحدد ما إذا كان سيتم تقليل الكسر أم لا. إذا كانت القيمة true، قد لا يتم تقليل الكسر. |
| [setAfterText](#setAfterText-java.lang.String-) | النص الذي سيُضمّن بعد التسمية |
| [setBeforeText](#setBeforeText-java.lang.String-) | النص الذي سيُضمّن إلى يسار التسمية. |
| [setConvresionFactor](#setConvresionFactor-double-) | عامل التحويل المستخدم لضرب قيمة بوحدات جزئية من العنصر السابق في مصفوفة تنسيق الأرقام للحصول على قيمة بوحدات تنسيق الأرقام هذا. |
| [setDenominator](#setDenominator-int-) | إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة هي مقام الكسر. القيمة الافتراضية هي 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة تحدد ما إذا كان سيتم تقليل الكسر أم لا. إذا كانت القيمة true، قد لا يتم تقليل الكسر. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | بالطريقة التي يتم بها عرض القيم الكسرية. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | النص الذي سيُستخدم كموقع عشري عند عرض القيم العددية. سلسلة فارغة تشير إلى أنه سيتم استخدام القيمة الافتراضية. القيمة الافتراضية هي حرف النقطة. |
| [setPrecision](#setPrecision-int-) | إذا كان FractionDisplayment هو ShowAsDecimal، فإن هذه القيمة هي دقة القيمة الكسرية؛ يجب أن تكون مضاعفًا للعدد 10. القيمة الافتراضية هي 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | النص الذي سيُستخدم بين فئات الآلاف عند عرض القيم العددية. سلسلة فارغة تشير إلى عدم إضافة أي نص. القيمة الافتراضية هي الفاصلة. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
منشئ لفئة NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

النص الذي سيُضمّن بعد التسمية

**Returns:**
كائن String

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

النص الذي سيُضمّن إلى يسار التسمية.

**Returns:**
كائن String

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

عامل التحويل المستخدم لضرب قيمة بوحدات جزئية من العنصر السابق في مصفوفة تنسيق الأرقام للحصول على قيمة بوحدات تنسيق الأرقام هذا.

**Returns:**
قيمة double

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة هي مقام الكسر. القيمة الافتراضية هي 16.

**Returns:**
قيمة int

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

بالطريقة التي يتم بها عرض القيم الكسرية.

**Returns:**
قيمة FractionStyle @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

النص الذي سيُستخدم كموقع عشري عند عرض القيم العددية. سلسلة فارغة تشير إلى أنه سيتم استخدام القيمة الافتراضية. القيمة الافتراضية هي حرف النقطة.

**Returns:**
قيمة سلسلة

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

إذا كان FractionDisplayment هو ShowAsDecimal، فإن هذه القيمة هي دقة القيمة الكسرية؛ يجب أن تكون مضاعفًا للعدد 10. القيمة الافتراضية هي 100.

**Returns:**
قيمة int

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

النص الذي سيُستخدم بين فئات الآلاف عند عرض القيم العددية. سلسلة فارغة تشير إلى عدم إضافة أي نص. القيمة الافتراضية هي الفاصلة.

**Returns:**
قيمة سلسلة

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

سلسلة نصية تحدد تسمية لعرض الوحدات.

**Returns:**
كائن String

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة تحدد ما إذا كان سيتم تقليل الكسر أم لا. إذا كانت القيمة true، قد لا يتم تقليل الكسر.

**Returns:**
قيمة منطقية

### setAfterText {#setAfterText-java.lang.String-}
النص الذي سيُضمّن بعد التسمية

### setBeforeText {#setBeforeText-java.lang.String-}
النص الذي سيُضمّن إلى يسار التسمية.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

عامل التحويل المستخدم لضرب قيمة بوحدات جزئية من العنصر السابق في مصفوفة تنسيق الأرقام للحصول على قيمة بوحدات تنسيق الأرقام هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة هي مقام الكسر. القيمة الافتراضية هي 16.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

إذا كان FractionDisplayment هو ShowAsFraction، فإن هذه القيمة تحدد ما إذا كان سيتم تقليل الكسر أم لا. إذا كانت القيمة true، قد لا يتم تقليل الكسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
بالطريقة التي يتم بها عرض القيم الكسرية.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
النص الذي سيُستخدم كموقع عشري عند عرض القيم العددية. سلسلة فارغة تشير إلى أنه سيتم استخدام القيمة الافتراضية. القيمة الافتراضية هي حرف النقطة.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

إذا كان FractionDisplayment هو ShowAsDecimal، فإن هذه القيمة هي دقة القيمة الكسرية؛ يجب أن تكون مضاعفًا للعدد 10. القيمة الافتراضية هي 100.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
النص الذي سيُستخدم بين فئات الآلاف عند عرض القيم العددية. سلسلة فارغة تشير إلى عدم إضافة أي نص. القيمة الافتراضية هي الفاصلة.

### setUnitLabel {#setUnitLabel-java.lang.String-}
