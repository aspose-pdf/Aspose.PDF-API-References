---
title: "SetTextMatrix"
linktitle: "SetTextMatrix"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator Tm (mengatur matriks teks)."
type: docs
weight: 750
url: /id/java/com.aspose.pdf.operators/settextmatrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.SetTextMatrix, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.SetTextMatrix

```
public class SetTextMatrix extends TextPlaceOperator
```

Kelas yang mewakili operator Tm (mengatur matriks teks).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetTextMatrix](#SetTextMatrix-double-double-double-double-double-double-) | Menginisialisasi operator. |
| [SetTextMatrix](#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-) | Menginisialisasi operator. |
| [SetTextMatrix](#SetTextMatrix-com.aspose.pdf.Matrix-) | Menginisialisasi operator dengan matriks. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getMatrix](#getMatrix--) | Argumen matriks dari operator. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argumen matriks dari operator. |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### SetTextMatrix {#SetTextMatrix-double-double-double-double-double-double-}
```
public SetTextMatrix(double a, double b, double c, double d, double e, double f)
```

Menginisialisasi operator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a |  | Koefisien A |
| b |  | Koefisien B |
| c |  | Koefisien C |
| d |  | Koefisien D |
| e |  | Koefisien E |
| f |  | Koefisien F |

### SetTextMatrix {#SetTextMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.SetTextMatrix-}
Menginisialisasi operator.

### SetTextMatrix {#SetTextMatrix-com.aspose.pdf.Matrix-}
Menginisialisasi operator dengan matriks.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Argumen matriks dari operator.

**Returns:**
Objek Matrix

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Argumen matriks dari operator.

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks operator.

**Returns:**
Representasi teks dari operator.
