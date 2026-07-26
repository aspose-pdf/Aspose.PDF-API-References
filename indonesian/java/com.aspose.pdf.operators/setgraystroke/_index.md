---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili tingkat abu-abu untuk operasi stroking."
type: docs
weight: 650
url: /id/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Kelas yang mewakili tingkat abu-abu untuk operasi stroking.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Menginisialisasi operator dengan warna yang ditentukan. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getColor](#getColor--) | Mengembalikan warna yang ditentukan oleh operator. |
| [getGray](#getGray--) | Mendapatkan atau mengatur tingkat nilai abu-abu. |
| [setGray](#setGray-double-) | Mendapatkan atau mengatur tingkat nilai abu-abu. |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Menginisialisasi operator dengan warna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| abu-abu |  | Tingkat nilai abu-abu. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
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

Mengembalikan representasi teks operator.

**Returns:**
Representasi teks dari operator.
