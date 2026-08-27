---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator c (tambahkan kurva ke jalur)."
type: docs
weight: 150
url: /id/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Kelas yang mewakili operator c (tambahkan kurva ke jalur).

## Fields

| Field | Deskripsi |
| --- | --- |
| [X1](#X1) | Mendapatkan atau mengatur koordinat X1. |
| [X2](#X2) | Mendapatkan atau mengatur koordinat X2. |
| [X3](#X3) | Mendapatkan atau mengatur koordinat X3. |
| [Y1](#Y1) | Mendapatkan atau mengatur koordinat Y1. |
| [Y2](#Y2) | Mendapatkan atau mengatur koordinat Y2. |
| [Y3](#Y3) | Mendapatkan atau mengatur koordinat Y3. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Menginisialisasi operator kurva. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### X1 {#X1}
```
public double X1
```

Mendapatkan atau mengatur koordinat X1.

### X2 {#X2}
```
public double X2
```

Mendapatkan atau mengatur koordinat X2.

### X3 {#X3}
```
public double X3
```

Mendapatkan atau mengatur koordinat X3.

### Y1 {#Y1}
```
public double Y1
```

Mendapatkan atau mengatur koordinat Y1.

### Y2 {#Y2}
```
public double Y2
```

Mendapatkan atau mengatur koordinat Y2.

### Y3 {#Y3}
```
public double Y3
```

Mendapatkan atau mengatur koordinat Y3.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Menginisialisasi operator kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 |  | Absidis titik pertama. |
| y1 |  | Ordinat titik pertama. |
| x2 |  | Absidis titik kedua. |
| y2 |  | Ordinat titik kedua. |
| x3 |  | Absidis titik ketiga. |
| y3 |  | Ordinat titik ketiga. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Hanya untuk penggunaan internal!

**Returns:**
ICommand nilai objek ICommand

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks operator.

**Returns:**
Representasi teks dari operator.
