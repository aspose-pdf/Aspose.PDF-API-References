---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل قيمة XMP"
type: docs
weight: 5750
url: /ar/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

يمثل قيمة XMP

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | منشئ لقيمة التاريخ والوقت. |
| [XmpValue](#XmpValue-double-) | منشئ لقيمة النقطة العائمة. |
| [XmpValue](#XmpValue-int-) | منشئ للقيمة integer. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | منشئ للقيمة string. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | يُهيئ قيمة XMP string جديدة. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | منشئ للقيمة array. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [isArray](#isArray--) | يرجع true إذا كان XmpValue هو array. |
| [isDateTime](#isDateTime--) | يرجع true إذا كانت القيمة DateTime. |
| [isDouble](#isDouble--) | يرجع true إذا كانت القيمة floating point. |
| [isField](#isField--) | يرجع true إذا كان XmpValue هو field. |
| [isInteger](#isInteger--) | يرجع true إذا كانت القيمة integer. |
| [isNamedValue](#isNamedValue--) | يرجع true إذا كان XmpValue هو named value. |
| [isNamedValues](#isNamedValues--) | يرجع true إذا كان XmpValue يمثل named values. |
| [isRaw](#isRaw--) | القيمة غير مدعومة/غير معروفة وتم توفير شفرة XML الخام. |
| [isString](#isString--) | يرجع true إذا كانت القيمة string. |
| [isStructure](#isStructure--) | يرجع true إذا كان XmpValue يمثل structure. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | يحوّل XmpValue إلى array. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | يحوّل XmpValue إلى array. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | احصل على مصفوفة KeyValuePair |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | يحوّل XmpValue إلى named value. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | يحوّل XmpValue إلى string. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | يحوّل DateTime إلى XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | يحوّل double إلى XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | يحوّل integer إلى XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | يحوّل array إلى XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | يحوّل string إلى XmpValue. |
| [toArray](#toArray--) | يرجع array. |
| [toDateTime](#toDateTime--) | يحوِّل إلى تاريخ ووقت. |
| [toDateTimeOffset](#toDateTimeOffset--) | يحوِّل قيمة XMP الحالية إلى تمثيل {@link DateTimeOffset}. |
| [toDictionary](#toDictionary--) | يرجع القاموس الذي يحتوي على القيم المسماة. |
| [toDouble](#toDouble--) | يحوِّل إلى double. |
| [toField](#toField--) | يرجع قيمة XMP كحقل XMP. |
| [toInteger](#toInteger--) | يحوِّل إلى integer. |
| [toNamedValue](#toNamedValue--) | يرجع قيمة XMP كقيمة مسماة. |
| [toNamedValueInternal](#toNamedValueInternal--) | للاستخدام الداخلي فقط |
| [toNamedValues](#toNamedValues--) | يرجع قيمة XMP كمجموعة قيم مسماة. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | رمز XML الخام للقيم غير المعروفة/غير المدعومة. |
| [toString](#toString--) | يرجع تمثيل السلسلة لـ XmpValue. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | يرجع تمثيل السلسلة لـ XmpValue. |
| [toStringValue](#toStringValue--) | يحوّل إلى سلسلة. |
| [toStructure](#toStructure--) | يرجع قيمة XMP كهيكل (مجموعة من الحقول). |

### XmpValue {#XmpValue-java.util.Date-}
منشئ لقيمة التاريخ والوقت.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

منشئ لقيمة النقطة العائمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

منشئ للقيمة integer.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة integer. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
منشئ للقيمة string.

### XmpValue {#XmpValue-java.lang.String-boolean-}
يُهيئ قيمة XMP string جديدة.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
منشئ للقيمة array.

### isArray {#isArray--}
```
public boolean isArray()
```

يرجع true إذا كان XmpValue هو array.

**Returns:**
قيمة منطقية

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

يرجع true إذا كانت القيمة DateTime.

**Returns:**
قيمة منطقية

### isDouble {#isDouble--}
```
public boolean isDouble()
```

يرجع true إذا كانت القيمة floating point.

**Returns:**
قيمة منطقية

### isField {#isField--}
```
public boolean isField()
```

يرجع true إذا كان XmpValue هو field.

**Returns:**
قيمة منطقية

### isInteger {#isInteger--}
```
public boolean isInteger()
```

يرجع true إذا كانت القيمة integer.

**Returns:**
قيمة منطقية

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

يرجع true إذا كان XmpValue هو named value.

**Returns:**
قيمة منطقية

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

يرجع true إذا كان XmpValue يمثل named values.

**Returns:**
قيمة منطقية

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

القيمة غير مدعومة/غير معروفة وتم توفير شفرة XML الخام.

**Returns:**
صحيح إذا تم إرجاع القيمة كبيانات خام.

### isString {#isString--}
```
public boolean isString()
```

يرجع true إذا كانت القيمة string.

**Returns:**
قيمة منطقية

### isStructure {#isStructure--}
```
public boolean isStructure()
```

يرجع true إذا كان XmpValue يمثل structure.

**Returns:**
قيمة منطقية

### to_ {#to_-com.aspose.pdf.XmpValue-}
يحوّل XmpValue إلى array.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
يحوّل XmpValue إلى array.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
احصل على مصفوفة KeyValuePair

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
يحوّل XmpValue إلى named value.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
يحوّل XmpValue إلى string.

### to_XmpValue {#to_XmpValue-java.util.Date-}
يحوّل DateTime إلى XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

يحوّل double إلى XmpValue.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double (القيمة للتحويل) |

**Returns:**
مثيل XmpValue

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

يحوّل integer إلى XmpValue.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int (القيمة للتحويل) |

**Returns:**
مثيل XmpValue

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
يحوّل array إلى XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
يحوّل string إلى XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

يرجع array.

**Returns:**
مصفوفة XmpValue

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

يحوِّل إلى تاريخ ووقت.

**Returns:**
مثيل Date

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

يحوِّل قيمة XMP الحالية إلى تمثيل {@link DateTimeOffset}.

**Returns:**
كائن {@link DateTimeOffset} يمثل قيمة XMP الحالية.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

يرجع القاموس الذي يحتوي على القيم المسماة.

**Returns:**
القاموس

### toDouble {#toDouble--}
```
public double toDouble()
```

يحوِّل إلى double.

**Returns:**
قيمة double

### toField {#toField--}
```
public XmpField toField()
```

يرجع قيمة XMP كحقل XMP.

**Returns:**
XmpField مثال

### toInteger {#toInteger--}
```
public int toInteger()
```

يحوِّل إلى integer.

**Returns:**
قيمة int

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

يرجع قيمة XMP كقيمة مسماة.

**Returns:**
(قيمة مسماة) مثيل HashMap بمفتاح String وقيمة XmpValue

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

للاستخدام الداخلي فقط

**Returns:**
للاستخدام الداخلي فقط

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

يرجع قيمة XMP كمجموعة قيم مسماة.

**Returns:**
(قيمة مجموعة مسماة) مثيل HashMap بمفتاح String وقيمة XmpValue

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

رمز XML الخام للقيم غير المعروفة/غير المدعومة.

**Returns:**
عقدة XML لهذه القيمة.

### toString {#toString--}
```
public String toString()
```

يرجع تمثيل السلسلة لـ XmpValue.

**Returns:**
تمثيل النص

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
يرجع تمثيل السلسلة لـ XmpValue.

**Returns:**
تمثيل النص

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

يحوّل إلى سلسلة.

**Returns:**
قيمة سلسلة

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

يرجع قيمة XMP كهيكل (مجموعة من الحقول).

**Returns:**
مصفوفة XmpField
