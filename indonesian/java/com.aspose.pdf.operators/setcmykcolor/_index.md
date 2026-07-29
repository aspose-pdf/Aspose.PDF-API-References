---
title: "SetCMYKColor"
linktitle: "SetCMYKColor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator k (mengatur warna CMYK untuk operasi non-stroking)."
type: docs
weight: 530
url: /id/java/com.aspose.pdf.operators/setcmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColor

```
public class SetCMYKColor extends SetColorOperator
```

Kelas yang mewakili operator k (mengatur warna CMYK untuk operasi non-stroking).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetCMYKColor](#SetCMYKColor-double-double-double-double-) | Menginisialisasi operator. |
| [SetCMYKColor](#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getC](#getC--) | Mendapatkan atau mengatur komponen cyan. |
| [getColor](#getColor--) | Mengembalikan warna. |
| [getK](#getK--) | Mendapatkan atau mengatur komponen hitam. |
| [getM](#getM--) | Mendapatkan atau mengatur komponen magenta. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Mendapatkan atau mengatur komponen kuning. |
| [setC](#setC-double-) | Mendapatkan atau mengatur komponen cyan. |
| [setK](#setK-double-) | Mendapatkan atau mengatur komponen hitam. |
| [setM](#setM-double-) | Mendapatkan atau mengatur komponen magenta. |
| [setY](#setY-double-) | Mendapatkan atau mengatur komponen kuning. |

### SetCMYKColor {#SetCMYKColor-double-double-double-double-}
```
public SetCMYKColor(double c, double m, double y, double k)
```

Menginisialisasi operator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c |  | Tingkat cyan dari 0.0 hingga 1.0 |
| m |  | Tingkat magenta dari 0.0 hingga 1.0 |
| y |  | Tingkat kuning dari 0.0 hingga 1.0 |
| k |  | Tingkat hitam dari 0.0 hingga 1.0 |

### SetCMYKColor {#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

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

Mengembalikan warna.

**Returns:**
Warna yang ditentukan oleh operator.

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

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Mendapatkan atau mengatur komponen kuning.

**Returns:**
nilai yang dapat dilakukan

### setC {#setC-double-}
```
public final void setC(double value)
```

Mendapatkan atau mengatur komponen cyan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang dapat dilakukan |

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

### setY {#setY-double-}
```
public final void setY(double value)
```

Mendapatkan atau mengatur komponen kuning.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang dapat dilakukan |
