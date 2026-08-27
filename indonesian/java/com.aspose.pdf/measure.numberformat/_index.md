---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Format angka untuk pengukuran."
type: docs
weight: 2940
url: /id/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Format angka untuk pengukuran.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Konstruktor untuk kelas NumberFormat. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAfterText](#getAfterText--) | Teks yang akan digabungkan setelah label |
| [getBeforeText](#getBeforeText--) | Teks yang akan digabungkan di sebelah kiri label. |
| [getConvresionFactor](#getConvresionFactor--) | Faktor konversi yang digunakan untuk mengalikan nilai dalam satuan parsial dari elemen array format angka sebelumnya untuk memperoleh nilai dalam satuan format angka ini. |
| [getDenominator](#getDenominator--) | Jika FractionDisplayment adalah ShowAsFraction, nilai ini adalah penyebut fraksi. Nilai default adalah 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | Cara nilai pecahan ditampilkan. |
| [getFractionSeparator](#getFractionSeparator--) | Teks yang akan digunakan sebagai posisi desimal dalam menampilkan nilai numerik. String kosong menunjukkan bahwa nilai default akan digunakan. Defaultnya adalah karakter titik. |
| [getPrecision](#getPrecision--) | Jika FractionDisplayment adalah ShowAsDecimal, nilai ini adalah presisi nilai pecahan; harus merupakan kelipatan 10. Defaultnya adalah 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Teks yang akan digunakan di antara ribuan dalam menampilkan nilai numerik. String kosong menunjukkan bahwa tidak ada teks yang akan ditambahkan. Defaultnya adalah koma. |
| [getUnitLabel](#getUnitLabel--) | String teks yang menentukan label untuk menampilkan satuan. |
| [isForceDenominator](#isForceDenominator--) | Jika FractionDisplayment adalah ShowAsFraction, nilai ini menentukan apakah fraksi akan disederhanakan atau tidak. Jika nilai true, fraksi tidak akan disederhanakan. |
| [setAfterText](#setAfterText-java.lang.String-) | Teks yang akan digabungkan setelah label |
| [setBeforeText](#setBeforeText-java.lang.String-) | Teks yang akan digabungkan di sebelah kiri label. |
| [setConvresionFactor](#setConvresionFactor-double-) | Faktor konversi yang digunakan untuk mengalikan nilai dalam satuan parsial dari elemen array format angka sebelumnya untuk memperoleh nilai dalam satuan format angka ini. |
| [setDenominator](#setDenominator-int-) | Jika FractionDisplayment adalah ShowAsFraction, nilai ini adalah penyebut fraksi. Nilai default adalah 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Jika FractionDisplayment adalah ShowAsFraction, nilai ini menentukan apakah fraksi akan disederhanakan atau tidak. Jika nilai true, fraksi tidak akan disederhanakan. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | Cara nilai pecahan ditampilkan. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Teks yang akan digunakan sebagai posisi desimal dalam menampilkan nilai numerik. String kosong menunjukkan bahwa nilai default akan digunakan. Defaultnya adalah karakter titik. |
| [setPrecision](#setPrecision-int-) | Jika FractionDisplayment adalah ShowAsDecimal, nilai ini adalah presisi nilai pecahan; harus merupakan kelipatan 10. Defaultnya adalah 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Teks yang akan digunakan di antara ribuan dalam menampilkan nilai numerik. String kosong menunjukkan bahwa tidak ada teks yang akan ditambahkan. Defaultnya adalah koma. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Konstruktor untuk kelas NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Teks yang akan digabungkan setelah label

**Returns:**
Objek String

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Teks yang akan digabungkan di sebelah kiri label.

**Returns:**
Objek String

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

Faktor konversi yang digunakan untuk mengalikan nilai dalam satuan parsial dari elemen array format angka sebelumnya untuk memperoleh nilai dalam satuan format angka ini.

**Returns:**
nilai double

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Jika FractionDisplayment adalah ShowAsFraction, nilai ini adalah penyebut fraksi. Nilai default adalah 16.

**Returns:**
nilai int

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

Cara nilai pecahan ditampilkan.

**Returns:**
Nilai FractionStyle @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Teks yang akan digunakan sebagai posisi desimal dalam menampilkan nilai numerik. String kosong menunjukkan bahwa nilai default akan digunakan. Defaultnya adalah karakter titik.

**Returns:**
nilai String

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Jika FractionDisplayment adalah ShowAsDecimal, nilai ini adalah presisi nilai pecahan; harus merupakan kelipatan 10. Defaultnya adalah 100.

**Returns:**
nilai int

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Teks yang akan digunakan di antara ribuan dalam menampilkan nilai numerik. String kosong menunjukkan bahwa tidak ada teks yang akan ditambahkan. Defaultnya adalah koma.

**Returns:**
nilai String

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

String teks yang menentukan label untuk menampilkan satuan.

**Returns:**
Objek String

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Jika FractionDisplayment adalah ShowAsFraction, nilai ini menentukan apakah fraksi akan disederhanakan atau tidak. Jika nilai true, fraksi tidak akan disederhanakan.

**Returns:**
nilai boolean

### setAfterText {#setAfterText-java.lang.String-}
Teks yang akan digabungkan setelah label

### setBeforeText {#setBeforeText-java.lang.String-}
Teks yang akan digabungkan di sebelah kiri label.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

Faktor konversi yang digunakan untuk mengalikan nilai dalam satuan parsial dari elemen array format angka sebelumnya untuk memperoleh nilai dalam satuan format angka ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Jika FractionDisplayment adalah ShowAsFraction, nilai ini adalah penyebut fraksi. Nilai default adalah 16.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Jika FractionDisplayment adalah ShowAsFraction, nilai ini menentukan apakah fraksi akan disederhanakan atau tidak. Jika nilai true, fraksi tidak akan disederhanakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
Cara nilai pecahan ditampilkan.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Teks yang akan digunakan sebagai posisi desimal dalam menampilkan nilai numerik. String kosong menunjukkan bahwa nilai default akan digunakan. Defaultnya adalah karakter titik.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Jika FractionDisplayment adalah ShowAsDecimal, nilai ini adalah presisi nilai pecahan; harus merupakan kelipatan 10. Defaultnya adalah 100.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Teks yang akan digunakan di antara ribuan dalam menampilkan nilai numerik. String kosong menunjukkan bahwa tidak ada teks yang akan ditambahkan. Defaultnya adalah koma.

### setUnitLabel {#setUnitLabel-java.lang.String-}
