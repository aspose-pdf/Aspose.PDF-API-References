---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator SC mengatur warna untuk operator warna stroking."
type: docs
weight: 600
url: /id/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

Kelas yang mewakili operator SC mengatur warna untuk operator warna stroking.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | Menginisialisasi operator. |
| [SetColorStroke](#SetColorStroke-double-) | Set warna untuk operator stroking untuk ruang warna DeviceGray, CalGray, dan Indexed. |
| [SetColorStroke](#SetColorStroke-double:A-) | Konstruktor yang memungkinkan untuk mengatur komponen warna. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | Set warna untuk operator stroking untuk ruang warna DeviceRGB, CalRGB, dan Lab. |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | Set warna untuk operator stroking untuk ruang warna CMYK. |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | Menginisialisasi operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getB](#getB--) | Mendapatkan atau mengatur komponen biru. Nilai: Tingkat biru dari 0.0 hingga 1.0 |
| [getC](#getC--) | Mendapatkan atau mengatur komponen cyan. |
| [getColor](#getColor--) | Mengembalikan warna yang ditentukan oleh operator. |
| [getG](#getG--) | Mendapatkan atau mengatur komponen hijau. Nilai: Tingkat hijau dari 0.0 hingga 1.0 |
| [getK](#getK--) | Mendapatkan atau mengatur komponen hitam. |
| [getM](#getM--) | Mendapatkan atau mengatur komponen magenta. |
| [getR](#getR--) | Mendapatkan atau mengatur komponen merah. Nilai: Tingkat merah dari 0.0 hingga 1.0 |
| [getY](#getY--) | Mendapatkan atau mengatur komponen kuning. |
| [setB](#setB-double-) | Mendapatkan atau mengatur komponen biru. Nilai: Tingkat biru dari 0.0 hingga 1.0 |
| [setC](#setC-double-) | Mendapatkan atau mengatur komponen cyan. |
| [setG](#setG-double-) | Mendapatkan atau mengatur komponen hijau. Nilai: Tingkat hijau dari 0.0 hingga 1.0 |
| [setK](#setK-double-) | Mendapatkan atau mengatur komponen hitam. |
| [setM](#setM-double-) | Mendapatkan atau mengatur komponen magenta. |
| [setR](#setR-double-) | Mendapatkan atau mengatur komponen merah. Nilai: Tingkat merah dari 0.0 hingga 1.0 |
| [setY](#setY-double-) | Mendapatkan atau mengatur komponen kuning. |

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

Menginisialisasi operator.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

Set warna untuk operator stroking untuk ruang warna DeviceGray, CalGray, dan Indexed.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g |  | Nilai warna. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

Konstruktor yang memungkinkan untuk mengatur komponen warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warna |  | Array komponen warna. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

Set warna untuk operator stroking untuk ruang warna DeviceRGB, CalRGB, dan Lab.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| r |  | Komponen merah. |
| g |  | Komponen hijau. |
| b |  | Komponen biru. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

Set warna untuk operator stroking untuk ruang warna CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c |  | Komponen cyan. |
| m |  | Komponen magenta. |
| y |  | Komponen kuning. |
| k |  | Komponen hitam. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
Menginisialisasi operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getB {#getB--}
```
public final double getB()
```

Mendapatkan atau mengatur komponen biru. Nilai: Tingkat biru dari 0.0 hingga 1.0

**Returns:**
nilai yang dapat dilakukan

### getC {#getC--}
```
public final double getC()
```

Mendapatkan atau mengatur komponen cyan.

**Returns:**
nilai yang dapat dilakukan

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

### getK {#getK--}
```
public final double getK()
```

Mendapatkan atau mengatur komponen hitam.

**Returns:**
nilai yang dapat dilakukan

### getM {#getM--}
```
public final double getM()
```

Mendapatkan atau mengatur komponen magenta.

**Returns:**
nilai yang dapat dilakukan

### getR {#getR--}
```
public final double getR()
```

Mendapatkan atau mengatur komponen merah. Nilai: Tingkat merah dari 0.0 hingga 1.0

**Returns:**
nilai yang dapat dilakukan

### getY {#getY--}
```
public final double getY()
```

Mendapatkan atau mengatur komponen kuning.

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

### setC {#setC-double-}
```
public final void setC(double value)
```

Mendapatkan atau mengatur komponen cyan.

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
| nilai |  | nilai double |

### setK {#setK-double-}
```
public final void setK(double value)
```

Mendapatkan atau mengatur komponen hitam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang dapat dilakukan |

### setM {#setM-double-}
```
public final void setM(double value)
```

Mendapatkan atau mengatur komponen magenta.

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

### setY {#setY-double-}
```
public final void setY(double value)
```

Mendapatkan atau mengatur komponen kuning.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang dapat dilakukan |
