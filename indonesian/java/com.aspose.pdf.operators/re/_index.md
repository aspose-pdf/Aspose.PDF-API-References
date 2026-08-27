---
title: "Re"
linktitle: "Re"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator re (menambahkan persegi panjang ke jalur)."
type: docs
weight: 460
url: /id/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Kelas yang mewakili operator re (menambahkan persegi panjang ke jalur).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Re](#Re--) | Konstruktor untuk mengekstrak tujuan. |
| [Re](#Re-double-double-double-double-) | Konstruktor untuk menulis program. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Konstruktor untuk mengekstrak tujuan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getHeight](#getHeight--) | Tinggi persegi panjang. |
| [getWidth](#getWidth--) | Mendapatkan lebar persegi panjang. |
| [getX](#getX--) | Koordinat X sisi paling kiri persegi panjang. |
| [getY](#getY--) | Koordinat Y sisi bawah persegi panjang. |
| [setHeight](#setHeight-double-) | Tinggi persegi panjang. |
| [setWidth](#setWidth-double-) | Mengatur lebar persegi panjang. |
| [setX](#setX-double-) | Koordinat X sisi paling kiri persegi panjang. |
| [setY](#setY-double-) | Koordinat Y sisi bawah persegi panjang. |
| [toString](#toString--) | Mengembalikan representasi teks dari operator. |

### Re {#Re--}
```
public Re()
```

Konstruktor untuk mengekstrak tujuan.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Konstruktor untuk menulis program.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Koordinat x dari sudut kiri-bawah persegi panjang. |
| y |  | Koordinat y dari sudut kiri-bawah persegi panjang. |
| lebar |  | Lebar persegi panjang. |
| tinggi |  | Tinggi persegi panjang. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Konstruktor untuk mengekstrak tujuan.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getHeight {#getHeight--}
```
public double getHeight()
```

Tinggi persegi panjang.

**Returns:**
Tinggi persegi panjang.

### getWidth {#getWidth--}
```
public double getWidth()
```

Mendapatkan lebar persegi panjang.

**Returns:**
lebar persegi panjang.

### getX {#getX--}
```
public double getX()
```

Koordinat X sisi paling kiri persegi panjang.

**Returns:**
nilai double

### getY {#getY--}
```
public double getY()
```

Koordinat Y sisi bawah persegi panjang.

**Returns:**
nilai double

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Tinggi persegi panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Tinggi persegi panjang. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Mengatur lebar persegi panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | lebar persegi panjang. |

### setX {#setX-double-}
```
public void setX(double value)
```

Koordinat X sisi paling kiri persegi panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setY {#setY-double-}
```
public void setY(double value)
```

Koordinat Y sisi bawah persegi panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks dari operator.

**Returns:**
Representasi teks dari operator.
