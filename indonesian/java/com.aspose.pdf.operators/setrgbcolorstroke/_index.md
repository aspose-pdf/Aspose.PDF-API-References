---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator RG (mengatur warna RGB untuk operator stroking)."
type: docs
weight: 720
url: /id/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

Kelas yang mewakili operator RG (mengatur warna RGB untuk operator stroking).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | Menginisialisasi operator dengan warna. |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | Konstruktor untuk menulis program. |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getB](#getB--) | Mendapatkan atau mengatur komponen biru. Nilai: Tingkat biru dari 0.0 hingga 1.0 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Mengembalikan warna yang ditentukan oleh operator. |
| [getG](#getG--) | Mendapatkan atau mengatur komponen hijau. Nilai: Tingkat hijau dari 0.0 hingga 1.0 |
| [getR](#getR--) | Mendapatkan atau mengatur komponen merah. Nilai: Tingkat merah dari 0.0 hingga 1.0 |
| [setB](#setB-double-) | Mendapatkan atau mengatur komponen biru. Nilai: Tingkat biru dari 0.0 hingga 1.0 |
| [setG](#setG-double-) | Mendapatkan atau mengatur komponen hijau. Nilai: Tingkat hijau dari 0.0 hingga 1.0 |
| [setR](#setR-double-) | Mendapatkan atau mengatur komponen merah. Nilai: Tingkat merah dari 0.0 hingga 1.0 |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
Menginisialisasi operator dengan warna.

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

Konstruktor untuk menulis program.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| r |  | Tingkat merah dari 0.0 hingga 1.0 |
| g |  | Tingkat hijau dari 0.0 hingga 1.0 |
| b |  | Tingkat biru dari 0.0 hingga 1.0 |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getB {#getB--}
```
public final double getB()
```

Mendapatkan atau mengatur komponen biru. Nilai: Tingkat biru dari 0.0 hingga 1.0

**Returns:**
nilai yang dapat dilakukan

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

Mengembalikan warna yang ditentukan oleh operator.

**Returns:**
Warna yang ditentukan oleh operator.

### getG {#getG--}
```
public final double getG()
```

Mendapatkan atau mengatur komponen hijau. Nilai: Tingkat hijau dari 0.0 hingga 1.0

**Returns:**
nilai yang dapat dilakukan

### getR {#getR--}
```
public final double getR()
```

Mendapatkan atau mengatur komponen merah. Nilai: Tingkat merah dari 0.0 hingga 1.0

**Returns:**
nilai yang dapat dilakukan

### setB {#setB-double-}
```
public final void setB(double value)
```

Mendapatkan atau mengatur komponen biru. Nilai: Tingkat biru dari 0.0 hingga 1.0

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang dapat dilakukan |

### setG {#setG-double-}
```
public final void setG(double value)
```

Mendapatkan atau mengatur komponen hijau. Nilai: Tingkat hijau dari 0.0 hingga 1.0

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang dapat dilakukan |

### setR {#setR-double-}
```
public final void setR(double value)
```

Mendapatkan atau mengatur komponen merah. Nilai: Tingkat merah dari 0.0 hingga 1.0

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang dapat dilakukan |

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks operator.

**Returns:**
Representasi teks dari operator.
