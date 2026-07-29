---
title: "ConcatenateMatrix"
linktitle: "ConcatenateMatrix"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator cm (menggabungkan matriks ke matriks transformasi saat ini)."
type: docs
weight: 140
url: /id/java/com.aspose.pdf.operators/concatenatematrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.ConcatenateMatrix, com.aspose.pdf.Operator, com.aspose.pdf.operators.ConcatenateMatrix

```
public class ConcatenateMatrix extends Operator
```

Kelas yang mewakili operator cm (menggabungkan matriks ke matriks transformasi saat ini).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ConcatenateMatrix](#ConcatenateMatrix-double-double-double-double-double-double-) | Konstruktor untuk kelas operator. |
| [ConcatenateMatrix](#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-) | Konstruktor untuk kelas operator. |
| [ConcatenateMatrix](#ConcatenateMatrix-com.aspose.pdf.Matrix-) | Menginisialisasi operator dengan matriks. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getMatrix](#getMatrix--) | Argumen matriks dari operator. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Argumen matriks dari operator. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### ConcatenateMatrix {#ConcatenateMatrix-double-double-double-double-double-double-}
```
public ConcatenateMatrix(double a, double b, double c, double d, double e, double f)
```

Konstruktor untuk kelas operator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a |  | Koefisien A |
| b |  | Koefisien B |
| c |  | Koefisien C |
| d |  | Koefisien D |
| e |  | Koefisien E |
| f |  | Koefisien F |

### ConcatenateMatrix {#ConcatenateMatrix-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.ModifyCurrentTransformationMatrix-}
Konstruktor untuk kelas operator.

### ConcatenateMatrix {#ConcatenateMatrix-com.aspose.pdf.Matrix-}
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
Representasi teks dari representasi
