---
title: "Arc"
linktitle: "Arc"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili busur."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Mewakili busur.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Arc](#Arc--) | Hanya untuk penggunaan internal |
| [Arc](#Arc-double-double-double-double-double-) | Menginisialisasi sebuah instance baru dari kelas {@code Arc}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Memeriksa apakah item cocok dengan dimensi kontainer yang diberikan (inklusif). |
| [getAlpha](#getAlpha--) | Mendapatkan nilai float yang menunjukkan derajat sudut awal dari busur. |
| [getBeta](#getBeta--) | Mendapatkan nilai float yang menunjukkan derajat sudut akhir dari busur. |
| [getPosX](#getPosX--) | Mendapatkan nilai float yang menunjukkan koordinat x dari pusat busur. |
| [getPosY](#getPosY--) | Mendapatkan nilai float yang menunjukkan koordinat y dari pusat busur. |
| [getRadius](#getRadius--) | Mendapatkan nilai float yang menunjukkan jari-jari busur. |
| [setAlpha](#setAlpha-double-) | Mengatur nilai float yang menunjukkan derajat sudut awal dari busur. |
| [setBeta](#setBeta-double-) | Mengatur nilai float yang menunjukkan derajat sudut akhir dari busur. |
| [setPosX](#setPosX-double-) | Mengatur nilai float yang menunjukkan koordinat x dari pusat busur. |
| [setPosY](#setPosY-double-) | Mengatur nilai float yang menunjukkan koordinat y dari pusat busur. |
| [setRadius](#setRadius-double-) | Mengatur nilai float yang menunjukkan jari-jari busur. |

### Arc {#Arc--}
```
public Arc()
```

Hanya untuk penggunaan internal

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Menginisialisasi sebuah instance baru dari kelas {@code Arc}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| posX |  | Koordinat x dari titik pusat busur. |
| posY |  | Koordinat y dari titik pusat busur. |
| radius |  | Nilai jari-jari busur. |
| alpha |  | Nilai sudut awal busur. |
| beta |  | Nilai sudut akhir busur. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Memeriksa apakah item cocok dengan dimensi kontainer yang diberikan (inklusif).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
True jika cocok; jika tidak, false.

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Mendapatkan nilai float yang menunjukkan derajat sudut awal dari busur.

**Returns:**
nilai alpha.

### getBeta {#getBeta--}
```
public double getBeta()
```

Mendapatkan nilai float yang menunjukkan derajat sudut akhir dari busur.

**Returns:**
nilai beta

### getPosX {#getPosX--}
```
public double getPosX()
```

Mendapatkan nilai float yang menunjukkan koordinat x dari pusat busur.

**Returns:**
Koordinat x dari pusat busur.

### getPosY {#getPosY--}
```
public double getPosY()
```

Mendapatkan nilai float yang menunjukkan koordinat y dari pusat busur.

**Returns:**
Koordinat y dari pusat busur.

### getRadius {#getRadius--}
```
public double getRadius()
```

Mendapatkan nilai float yang menunjukkan jari-jari busur.

**Returns:**
nilai yang menunjukkan jari-jari busur.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Mengatur nilai float yang menunjukkan derajat sudut awal dari busur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai alpha. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Mengatur nilai float yang menunjukkan derajat sudut akhir dari busur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai beta |

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Mengatur nilai float yang menunjukkan koordinat x dari pusat busur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Koordinat x dari pusat busur. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Mengatur nilai float yang menunjukkan koordinat y dari pusat busur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Koordinat y dari pusat busur. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Mengatur nilai float yang menunjukkan jari-jari busur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | yang menunjukkan jari-jari busur. |
