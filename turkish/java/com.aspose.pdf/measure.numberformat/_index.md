---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Aspose.PDF for Java API Referansı"
description: "Ölçüm için sayı formatı."
type: docs
weight: 2940
url: /tr/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Ölçüm için sayı formatı.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | NumberFormat sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAfterText](#getAfterText--) | Etiketin ardından birleştirilecek metin |
| [getBeforeText](#getBeforeText--) | Etiketin soluna birleştirilecek metin. |
| [getConvresionFactor](#getConvresionFactor--) | Bu sayı formatının birimlerinde bir değer elde etmek için, önceki sayı formatı dizi öğesinin kısmi birimlerindeki bir değeri çarpmak amacıyla kullanılan dönüşüm faktörü. |
| [getDenominator](#getDenominator--) | FractionDisplayment ShowAsFraction ise, bu değer kesrin paydasını belirtir. Varsayılan değer 16'dır. |
| [getFractionDisplayment](#getFractionDisplayment--) | Kesir değerlerinin nasıl görüntüleneceği. |
| [getFractionSeparator](#getFractionSeparator--) | Sayısal değerleri gösterirken ondalık konum olarak kullanılacak metin. Boş bir dize, varsayılanın kullanılacağını gösterir. Varsayılan nokta karakteridir. |
| [getPrecision](#getPrecision--) | FractionDisplayment ShowAsDecimal ise, bu değer kesir değerinin hassasiyetidir; 10'un katı olmalıdır. Varsayılan 100'dür. |
| [getThousandsSeparator](#getThousandsSeparator--) | Sayısal değerlerin gösteriminde binlik basamak grupları arasında kullanılacak metin. Boş bir dize, metin eklenmeyeceğini gösterir. Varsayılan virgüldür. |
| [getUnitLabel](#getUnitLabel--) | Birimleri göstermek için bir etiket belirten metin dizesi. |
| [isForceDenominator](#isForceDenominator--) | FractionDisplayment ShowAsFraction ise, bu değer kesrin azaltılıp azaltılmayacağını belirler. Değer true ise kesir azaltılamaz. |
| [setAfterText](#setAfterText-java.lang.String-) | Etiketin ardından birleştirilecek metin |
| [setBeforeText](#setBeforeText-java.lang.String-) | Etiketin soluna birleştirilecek metin. |
| [setConvresionFactor](#setConvresionFactor-double-) | Bu sayı formatının birimlerinde bir değer elde etmek için, önceki sayı formatı dizi öğesinin kısmi birimlerindeki bir değeri çarpmak amacıyla kullanılan dönüşüm faktörü. |
| [setDenominator](#setDenominator-int-) | FractionDisplayment ShowAsFraction ise, bu değer kesrin paydasını belirtir. Varsayılan değer 16'dır. |
| [setForceDenominator](#setForceDenominator-boolean-) | FractionDisplayment ShowAsFraction ise, bu değer kesrin azaltılıp azaltılmayacağını belirler. Değer true ise kesir azaltılamaz. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | Kesir değerlerinin nasıl görüntüleneceği. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Sayısal değerleri gösterirken ondalık konum olarak kullanılacak metin. Boş bir dize, varsayılanın kullanılacağını gösterir. Varsayılan nokta karakteridir. |
| [setPrecision](#setPrecision-int-) | FractionDisplayment ShowAsDecimal ise, bu değer kesir değerinin hassasiyetidir; 10'un katı olmalıdır. Varsayılan 100'dür. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Sayısal değerlerin gösteriminde binlik basamak grupları arasında kullanılacak metin. Boş bir dize, metin eklenmeyeceğini gösterir. Varsayılan virgüldür. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
NumberFormat sınıfı için yapıcı.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Etiketin ardından birleştirilecek metin

**Returns:**
Dize nesnesi

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Etiketin soluna birleştirilecek metin.

**Returns:**
Dize nesnesi

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

Bu sayı formatının birimlerinde bir değer elde etmek için, önceki sayı formatı dizi öğesinin kısmi birimlerindeki bir değeri çarpmak amacıyla kullanılan dönüşüm faktörü.

**Returns:**
double değer

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

FractionDisplayment ShowAsFraction ise, bu değer kesrin paydasını belirtir. Varsayılan değer 16'dır.

**Returns:**
int değer

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

Kesir değerlerinin nasıl görüntüleneceği.

**Returns:**
FractionStyle değeri @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Sayısal değerleri gösterirken ondalık konum olarak kullanılacak metin. Boş bir dize, varsayılanın kullanılacağını gösterir. Varsayılan nokta karakteridir.

**Returns:**
String değeri

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

FractionDisplayment ShowAsDecimal ise, bu değer kesir değerinin hassasiyetidir; 10'un katı olmalıdır. Varsayılan 100'dür.

**Returns:**
int değer

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Sayısal değerlerin gösteriminde binlik basamak grupları arasında kullanılacak metin. Boş bir dize, metin eklenmeyeceğini gösterir. Varsayılan virgüldür.

**Returns:**
String değeri

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

Birimleri göstermek için bir etiket belirten metin dizesi.

**Returns:**
Dize nesnesi

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

FractionDisplayment ShowAsFraction ise, bu değer kesrin azaltılıp azaltılmayacağını belirler. Değer true ise kesir azaltılamaz.

**Returns:**
boolean değer

### setAfterText {#setAfterText-java.lang.String-}
Etiketin ardından birleştirilecek metin

### setBeforeText {#setBeforeText-java.lang.String-}
Etiketin soluna birleştirilecek metin.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

Bu sayı formatının birimlerinde bir değer elde etmek için, önceki sayı formatı dizi öğesinin kısmi birimlerindeki bir değeri çarpmak amacıyla kullanılan dönüşüm faktörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

FractionDisplayment ShowAsFraction ise, bu değer kesrin paydasını belirtir. Varsayılan değer 16'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

FractionDisplayment ShowAsFraction ise, bu değer kesrin azaltılıp azaltılmayacağını belirler. Değer true ise kesir azaltılamaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
Kesir değerlerinin nasıl görüntüleneceği.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Sayısal değerleri gösterirken ondalık konum olarak kullanılacak metin. Boş bir dize, varsayılanın kullanılacağını gösterir. Varsayılan nokta karakteridir.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

FractionDisplayment ShowAsDecimal ise, bu değer kesir değerinin hassasiyetidir; 10'un katı olmalıdır. Varsayılan 100'dür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Sayısal değerlerin gösteriminde binlik basamak grupları arasında kullanılacak metin. Boş bir dize, metin eklenmeyeceğini gösterir. Varsayılan virgüldür.

### setUnitLabel {#setUnitLabel-java.lang.String-}
