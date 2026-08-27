---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili nilai XMP"
type: docs
weight: 5750
url: /id/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

Mewakili nilai XMP

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Konstruktor untuk nilai tanggal dan waktu. |
| [XmpValue](#XmpValue-double-) | Konstruktor untuk nilai titik mengambang. |
| [XmpValue](#XmpValue-int-) | Konstruktor untuk nilai integer. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Konstruktor untuk nilai string. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Menginisialisasi nilai XMP string baru. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Konstruktor untuk nilai array. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [isArray](#isArray--) | Mengembalikan true jika XmpValue adalah array. |
| [isDateTime](#isDateTime--) | Mengembalikan true jika nilai adalah DateTime. |
| [isDouble](#isDouble--) | Mengembalikan true jika nilai adalah nilai titik mengambang. |
| [isField](#isField--) | Mengembalikan true jika XmpValue adalah field. |
| [isInteger](#isInteger--) | Mengembalikan true jika nilai adalah integer. |
| [isNamedValue](#isNamedValue--) | Mengembalikan true jika XmpValue adalah nilai bernama. |
| [isNamedValues](#isNamedValues--) | Mengembalikan true jika XmpValue mewakili nilai-nilai bernama. |
| [isRaw](#isRaw--) | Nilai tidak didukung/tidak diketahui dan kode XML mentah disediakan. |
| [isString](#isString--) | Mengembalikan true jika nilai adalah string. |
| [isStructure](#isStructure--) | Mengembalikan true jika XmpValue mewakili struktur. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | Mengonversi XmpValue menjadi array. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | Mengonversi XmpValue ke array. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | Dapatkan array KeyValuePair |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | Mengonversi XmpValue ke nilai bernama. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | Mengonversi XmpValue menjadi string. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | Mengonversi DateTime menjadi XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | Mengonversi double menjadi XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | Mengonversi integer menjadi XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Mengonversi array ke XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Mengonversi string ke XmpValue. |
| [toArray](#toArray--) | Mengembalikan array. |
| [toDateTime](#toDateTime--) | Mengonversi ke tanggal waktu. |
| [toDateTimeOffset](#toDateTimeOffset--) | Mengonversi nilai XMP saat ini ke representasi {@link DateTimeOffset}. |
| [toDictionary](#toDictionary--) | Mengembalikan kamus yang berisi nilai bernama. |
| [toDouble](#toDouble--) | Mengonversi ke double. |
| [toField](#toField--) | Mengembalikan nilai XMP sebagai bidang XMP. |
| [toInteger](#toInteger--) | Mengonversi ke integer. |
| [toNamedValue](#toNamedValue--) | Mengembalikan nilai XMP sebagai nilai bernama. |
| [toNamedValueInternal](#toNamedValueInternal--) | Hanya untuk penggunaan internal |
| [toNamedValues](#toNamedValues--) | Mengembalikan nilai XMP sebagai koleksi nilai bernama. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Kode XML mentah untuk nilai yang tidak diketahui/tidak didukung. |
| [toString](#toString--) | Mengembalikan representasi string dari XmpValue. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | Mengembalikan representasi string dari XmpValue. |
| [toStringValue](#toStringValue--) | Mengonversi menjadi string. |
| [toStructure](#toStructure--) | Mengembalikan nilai XMP sebagai struktur (sekumpulan bidang). |

### XmpValue {#XmpValue-java.util.Date-}
Konstruktor untuk nilai tanggal dan waktu.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Konstruktor untuk nilai titik mengambang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai double. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Konstruktor untuk nilai integer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai integer. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Konstruktor untuk nilai string.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Menginisialisasi nilai XMP string baru.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Konstruktor untuk nilai array.

### isArray {#isArray--}
```
public boolean isArray()
```

Mengembalikan true jika XmpValue adalah array.

**Returns:**
nilai boolean

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Mengembalikan true jika nilai adalah DateTime.

**Returns:**
nilai boolean

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Mengembalikan true jika nilai adalah nilai titik mengambang.

**Returns:**
nilai boolean

### isField {#isField--}
```
public boolean isField()
```

Mengembalikan true jika XmpValue adalah field.

**Returns:**
nilai boolean

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Mengembalikan true jika nilai adalah integer.

**Returns:**
nilai boolean

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

Mengembalikan true jika XmpValue adalah nilai bernama.

**Returns:**
nilai boolean

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

Mengembalikan true jika XmpValue mewakili nilai-nilai bernama.

**Returns:**
nilai boolean

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

Nilai tidak didukung/tidak diketahui dan kode XML mentah disediakan.

**Returns:**
Benar jika nilai dikembalikan sebagai data mentah.

### isString {#isString--}
```
public boolean isString()
```

Mengembalikan true jika nilai adalah string.

**Returns:**
nilai boolean

### isStructure {#isStructure--}
```
public boolean isStructure()
```

Mengembalikan true jika XmpValue mewakili struktur.

**Returns:**
nilai boolean

### to_ {#to_-com.aspose.pdf.XmpValue-}
Mengonversi XmpValue menjadi array.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
Mengonversi XmpValue ke array.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
Dapatkan array KeyValuePair

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
Mengonversi XmpValue ke nilai bernama.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
Mengonversi XmpValue menjadi string.

### to_XmpValue {#to_XmpValue-java.util.Date-}
Mengonversi DateTime menjadi XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Mengonversi double menjadi XmpValue.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double (Nilai untuk dikonversi) |

**Returns:**
Instansi XmpValue

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Mengonversi integer menjadi XmpValue.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int (Nilai untuk dikonversi) |

**Returns:**
Instansi XmpValue

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Mengonversi array ke XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Mengonversi string ke XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Mengembalikan array.

**Returns:**
Array XmpValue

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Mengonversi ke tanggal waktu.

**Returns:**
Instansi Date

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Mengonversi nilai XMP saat ini ke representasi {@link DateTimeOffset}.

**Returns:**
Sebuah {@link DateTimeOffset} yang mewakili nilai XMP saat ini.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Mengembalikan kamus yang berisi nilai bernama.

**Returns:**
Kamus

### toDouble {#toDouble--}
```
public double toDouble()
```

Mengonversi ke double.

**Returns:**
nilai double

### toField {#toField--}
```
public XmpField toField()
```

Mengembalikan nilai XMP sebagai bidang XMP.

**Returns:**
instance XmpField

### toInteger {#toInteger--}
```
public int toInteger()
```

Mengonversi ke integer.

**Returns:**
nilai int

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

Mengembalikan nilai XMP sebagai nilai bernama.

**Returns:**
(Nilai bernama) instansi HashMap dengan Kunci String dan nilai XmpValue

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Hanya untuk penggunaan internal

**Returns:**
Hanya untuk penggunaan internal

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

Mengembalikan nilai XMP sebagai koleksi nilai bernama.

**Returns:**
(Nilai koleksi bernama) instansi HashMap dengan Kunci String dan nilai XmpValue

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Kode XML mentah untuk nilai yang tidak diketahui/tidak didukung.

**Returns:**
Node XML untuk nilai ini.

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi string dari XmpValue.

**Returns:**
Representasi string

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
Mengembalikan representasi string dari XmpValue.

**Returns:**
Representasi string

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Mengonversi menjadi string.

**Returns:**
nilai String

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

Mengembalikan nilai XMP sebagai struktur (sekumpulan bidang).

**Returns:**
Array XmpField
