---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Aspose.PDF for Java API Referansı"
description: "XMP değerini temsil eder"
type: docs
weight: 5750
url: /tr/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

XMP değerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Tarih saat değeri için yapıcı. |
| [XmpValue](#XmpValue-double-) | Kayan nokta değeri için yapıcı. |
| [XmpValue](#XmpValue-int-) | Tam sayı değeri için yapıcı. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Dize değeri için yapıcı. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Yeni dize XMP değerini başlatır. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Dizi değeri için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isArray](#isArray--) | XmpValue bir dizi ise true döndürür. |
| [isDateTime](#isDateTime--) | Değer DateTime ise true döndürür. |
| [isDouble](#isDouble--) | Değer kayan nokta değeri ise true döndürür. |
| [isField](#isField--) | XmpValue bir alan ise true döndürür. |
| [isInteger](#isInteger--) | Değer tam sayı ise true döndürür. |
| [isNamedValue](#isNamedValue--) | XmpValue adlandırılmış değer ise true döndürür. |
| [isNamedValues](#isNamedValues--) | XmpValue adlandırılmış değerleri temsil ediyorsa true döndürür. |
| [isRaw](#isRaw--) | Değer desteklenmiyor/bilinmiyor ve ham XML kodu sağlanıyor. |
| [isString](#isString--) | Değer dize ise true döndürür. |
| [isStructure](#isStructure--) | XmpValue yapıyı temsil ediyorsa true döndürür. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | XmpValue'ı diziye dönüştürür. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | XmpValue'ı diziye dönüştürür. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | KeyValuePair dizisini al |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | XmpValue'ı adlandırılmış değere dönüştürür. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | XmpValue'ı dizeye dönüştürür. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | DateTime'ı XmpValue'ye dönüştürür. |
| [to_XmpValue](#to_XmpValue-double-) | Double'ı XmpValue'ye dönüştürür. |
| [to_XmpValue](#to_XmpValue-int-) | Tam sayıyı XmpValue'ye dönüştürür. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Diziyi XmpValue'ye dönüştürür. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Dizeyi XmpValue'ye dönüştürür. |
| [toArray](#toArray--) | Dizi döndürür. |
| [toDateTime](#toDateTime--) | Tarih saatine dönüştürür. |
| [toDateTimeOffset](#toDateTimeOffset--) | Geçerli XMP değerini bir {@link DateTimeOffset} temsiline dönüştürür. |
| [toDictionary](#toDictionary--) | Adlandırılmış değerleri içeren sözlüğü döndürür. |
| [toDouble](#toDouble--) | Double'a dönüştürür. |
| [toField](#toField--) | XMP değerini XMP alanı olarak döndürür. |
| [toInteger](#toInteger--) | Integer'a dönüştürür. |
| [toNamedValue](#toNamedValue--) | XMP değerini adlandırılmış değer olarak döndürür. |
| [toNamedValueInternal](#toNamedValueInternal--) | Yalnızca dahili kullanım için |
| [toNamedValues](#toNamedValues--) | XMP değerini adlandırılmış değer koleksiyonu olarak döndürür. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Bilinmeyen/desteklenmeyen değerler için ham XML kodu. |
| [toString](#toString--) | XmpValue'nin dize temsilini döndürür. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | XmpValue'nin dize temsilini döndürür. |
| [toStringValue](#toStringValue--) | Dizeye dönüştürür. |
| [toStructure](#toStructure--) | XMP değerini yapı (alan kümesi) olarak döndürür. |

### XmpValue {#XmpValue-java.util.Date-}
Tarih saat değeri için yapıcı.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Kayan nokta değeri için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Double değeri. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Tam sayı değeri için yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Integer değeri. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Dize değeri için yapıcı.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Yeni dize XMP değerini başlatır.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Dizi değeri için yapıcı.

### isArray {#isArray--}
```
public boolean isArray()
```

XmpValue bir dizi ise true döndürür.

**Returns:**
boolean değer

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Değer DateTime ise true döndürür.

**Returns:**
boolean değer

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Değer kayan nokta değeri ise true döndürür.

**Returns:**
boolean değer

### isField {#isField--}
```
public boolean isField()
```

XmpValue bir alan ise true döndürür.

**Returns:**
boolean değer

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Değer tam sayı ise true döndürür.

**Returns:**
boolean değer

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

XmpValue adlandırılmış değer ise true döndürür.

**Returns:**
boolean değer

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

XmpValue adlandırılmış değerleri temsil ediyorsa true döndürür.

**Returns:**
boolean değer

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

Değer desteklenmiyor/bilinmiyor ve ham XML kodu sağlanıyor.

**Returns:**
Değer ham veri olarak döndürülmüşse doğru.

### isString {#isString--}
```
public boolean isString()
```

Değer dize ise true döndürür.

**Returns:**
boolean değer

### isStructure {#isStructure--}
```
public boolean isStructure()
```

XmpValue yapıyı temsil ediyorsa true döndürür.

**Returns:**
boolean değer

### to_ {#to_-com.aspose.pdf.XmpValue-}
XmpValue'ı diziye dönüştürür.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
XmpValue'ı diziye dönüştürür.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
KeyValuePair dizisini al

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
XmpValue'ı adlandırılmış değere dönüştürür.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
XmpValue'ı dizeye dönüştürür.

### to_XmpValue {#to_XmpValue-java.util.Date-}
DateTime'ı XmpValue'ye dönüştürür.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Double'ı XmpValue'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değeri (Dönüştürülecek değer) |

**Returns:**
XmpValue örneği

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Tam sayıyı XmpValue'ye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değeri (Dönüştürülecek değer) |

**Returns:**
XmpValue örneği

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Diziyi XmpValue'ye dönüştürür.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Dizeyi XmpValue'ye dönüştürür.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Dizi döndürür.

**Returns:**
XmpValue dizisi

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Tarih saatine dönüştürür.

**Returns:**
Date örneği

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Geçerli XMP değerini bir {@link DateTimeOffset} temsiline dönüştürür.

**Returns:**
Geçerli XMP değerini temsil eden bir {@link DateTimeOffset}.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Adlandırılmış değerleri içeren sözlüğü döndürür.

**Returns:**
Sözlük

### toDouble {#toDouble--}
```
public double toDouble()
```

Double'a dönüştürür.

**Returns:**
double değer

### toField {#toField--}
```
public XmpField toField()
```

XMP değerini XMP alanı olarak döndürür.

**Returns:**
XmpField örneği

### toInteger {#toInteger--}
```
public int toInteger()
```

Integer'a dönüştürür.

**Returns:**
int değer

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

XMP değerini adlandırılmış değer olarak döndürür.

**Returns:**
(Adlandırılmış değer) String anahtar ve XmpValue değerine sahip HashMap örneği

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Yalnızca dahili kullanım için

**Returns:**
Yalnızca dahili kullanım için

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

XMP değerini adlandırılmış değer koleksiyonu olarak döndürür.

**Returns:**
(Adlandırılmış koleksiyon değeri) String anahtar ve XmpValue değerine sahip HashMap örneği

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Bilinmeyen/desteklenmeyen değerler için ham XML kodu.

**Returns:**
Bu değer için XML düğümü.

### toString {#toString--}
```
public String toString()
```

XmpValue'nin dize temsilini döndürür.

**Returns:**
Dize temsili

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
XmpValue'nin dize temsilini döndürür.

**Returns:**
Dize temsili

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Dizeye dönüştürür.

**Returns:**
String değeri

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

XMP değerini yapı (alan kümesi) olarak döndürür.

**Returns:**
XmpField dizisi
