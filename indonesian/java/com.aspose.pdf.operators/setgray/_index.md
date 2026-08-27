---
title: "SetGray"
linktitle: "SetGray"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Atur tingkat abu-abu untuk operasi non-stroking."
type: docs
weight: 640
url: /id/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Atur tingkat abu-abu untuk operasi non-stroking.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetGray](#SetGray-double-) | Konstruktor untuk menulis program. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getColor](#getColor--) | Mengembalikan warna yang ditentukan oleh operator. |
| [getGray](#getGray--) | Mendapatkan atau mengatur tingkat nilai abu-abu. |
| [setGray](#setGray-double-) | Mendapatkan atau mengatur tingkat nilai abu-abu. |
| [toString](#toString--) | Mengembalikan representasi string dari operator. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Konstruktor untuk menulis program.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| abu-abu |  | Tingkat nilai abu-abu. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getColor {#getColor--}
```
public Color getColor()
```

Mengembalikan warna yang ditentukan oleh operator.

**Returns:**
Warna yang ditentukan oleh operator.

### getGray {#getGray--}
```
public final double getGray()
```

Mendapatkan atau mengatur tingkat nilai abu-abu.

**Returns:**
nilai double

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Mendapatkan atau mengatur tingkat nilai abu-abu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi string dari operator.

**Returns:**
Representasi string dari operator.
