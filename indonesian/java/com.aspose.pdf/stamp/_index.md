---
title: "Stempel"
linktitle: "Stempel"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas abstrak untuk berbagai jenis stempel yang muncul sebagai turunan."
type: docs
weight: 4620
url: /id/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

Kelas abstrak untuk berbagai jenis stempel yang muncul sebagai turunan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Mendapatkan margin bawah stempel. |
| [getHeight](#getHeight--) | Mendapatkan tinggi yang diinginkan dari stempel pada halaman. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Mendapatkan perataan horizontal stempel pada halaman. |
| [getLeftMargin](#getLeftMargin--) | Mendapatkan margin kiri stempel. |
| [getOpacity](#getOpacity--) | Mendapatkan nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Mendapatkan nilai untuk menunjukkan opasitas garis luar stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | Mendapatkan nilai lebar garis luar stempel. Secara default nilai adalah 1.0. |
| [getRightMargin](#getRightMargin--) | Mendapatkan margin kanan stempel. |
| [getRotate](#getRotate--) | Mendapatkan rotasi konten stempel sesuai nilai {@code Rotation}. Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut arbitrer gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | Mendapatkan sudut rotasi stempel dalam derajat. Properti ini memungkinkan mengatur sudut rotasi arbitrer. |
| [getStampId](#getStampId--) | Mendapatkan ID stempel. |
| [getTopMargin](#getTopMargin--) | Mendapatkan margin atas stempel. |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan perataan vertikal stempel pada halaman. |
| [getWidth](#getWidth--) | Mendapatkan lebar yang diinginkan dari stempel pada halaman. |
| [getXIndent](#getXIndent--) | Mendapatkan koordinat horizontal stempel, dimulai dari kiri. |
| [getYIndent](#getYIndent--) | Mendapatkan koordinat vertikal stempel, dimulai dari bawah. |
| [getZoom](#getZoom--) | Mendapatkan faktor zoom stempel. Memungkinkan memperbesar skala stempel. Harap perhatikan bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [getZoomX](#getZoomX--) | Mendapatkan faktor zoom horizontal stempel. Memungkinkan memperbesar skala stempel secara horizontal. |
| [getZoomY](#getZoomY--) | Mendapatkan faktor zoom vertikal stempel. Memungkinkan memperbesar skala stempel secara vertikal. |
| [isBackground](#isBackground--) | Mendapatkan nilai bool yang menunjukkan konten ditempelkan sebagai latar belakang. Jika nilai true, konten stempel diletakkan di bagian bawah. Secara default, nilai false, konten stempel diletakkan di bagian atas. |
| [put](#put-com.aspose.pdf.Page-) | Menambahkan stempel pada halaman. |
| [setBackground](#setBackground-boolean-) | Mengatur nilai bool yang menunjukkan konten ditempelkan sebagai latar belakang. Jika nilai true, konten stempel diletakkan di bagian bawah. Secara default, nilai false, konten stempel diletakkan di bagian atas. |
| [setBottomMargin](#setBottomMargin-double-) | Mengatur margin bawah stempel. |
| [setHeight](#setHeight-double-) | Mengatur tinggi yang diinginkan dari stempel pada halaman. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan horizontal stempel pada halaman. |
| [setLeftMargin](#setLeftMargin-double-) | Mengatur margin kiri stempel. |
| [setOpacity](#setOpacity-double-) | Mengatur nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Mengatur nilai untuk menunjukkan opasitas garis tepi stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Mengatur nilai lebar garis tepi stempel. Secara default nilai adalah 1.0. |
| [setRightMargin](#setRightMargin-double-) | Mengatur margin kanan stempel. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Mengatur rotasi konten stempel sesuai nilai {@code Rotation}. Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut arbitrer gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | Mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan mengatur sudut rotasi arbitrer. |
| [setStampId](#setStampId-int-) | Mengatur Id stempel. |
| [setTopMargin](#setTopMargin-double-) | Mengatur margin atas stempel. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mengatur perataan vertikal stempel pada halaman. |
| [setWidth](#setWidth-double-) | Mengatur lebar yang diinginkan dari stempel pada halaman. |
| [setXIndent](#setXIndent-double-) | Atur koordinat horizontal stempel, mulai dari kiri. |
| [setYIndent](#setYIndent-double-) | Atur koordinat vertikal stempel, mulai dari bawah. |
| [setZoom](#setZoom-double-) | Mendapatkan faktor zoom stempel. Memungkinkan memperbesar skala stempel. Harap perhatikan bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX. |
| [setZoomX](#setZoomX-double-) | Mengatur faktor zoom horizontal stempel. Memungkinkan memperbesar stempel secara horizontal. |
| [setZoomY](#setZoomY-double-) | Mengatur faktor zoom vertikal stempel. Memungkinkan memperbesar stempel secara vertikal. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Mendapatkan margin bawah stempel.

**Returns:**
nilai double

### getHeight {#getHeight--}
```
public double getHeight()
```

Mendapatkan tinggi yang diinginkan dari stempel pada halaman.

**Returns:**
nilai double

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Mendapatkan perataan horizontal stempel pada halaman.

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Mendapatkan margin kiri stempel.

**Returns:**
nilai double

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Mendapatkan nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0.

**Returns:**
nilai double

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Mendapatkan nilai untuk menunjukkan opasitas garis luar stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0.

**Returns:**
nilai double

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Mendapatkan nilai lebar garis luar stempel. Secara default nilai adalah 1.0.

**Returns:**
nilai double

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Mendapatkan margin kanan stempel.

**Returns:**
nilai double

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Mendapatkan rotasi konten stempel sesuai nilai {@code Rotation}. Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut arbitrer gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None.

**Returns:**
Nilai Rotasi @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Mendapatkan sudut rotasi stempel dalam derajat. Properti ini memungkinkan mengatur sudut rotasi arbitrer.

**Returns:**
nilai double

### getStampId {#getStampId--}
```
public int getStampId()
```

Mendapatkan ID stempel.

**Returns:**
Pengidentifikasi stempel.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Mendapatkan margin atas stempel.

**Returns:**
nilai double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Mendapatkan perataan vertikal stempel pada halaman.

**Returns:**
Nilai VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Mendapatkan lebar yang diinginkan dari stempel pada halaman.

**Returns:**
nilai double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Mendapatkan koordinat horizontal stempel, dimulai dari kiri.

**Returns:**
nilai double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Mendapatkan koordinat vertikal stempel, dimulai dari bawah.

**Returns:**
nilai double

### getZoom {#getZoom--}
```
public double getZoom()
```

Mendapatkan faktor zoom stempel. Memungkinkan memperbesar skala stempel. Harap perhatikan bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX.

**Returns:**
nilai double

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Mendapatkan faktor zoom horizontal stempel. Memungkinkan memperbesar skala stempel secara horizontal.

**Returns:**
nilai double

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Mendapatkan faktor zoom vertikal stempel. Memungkinkan memperbesar skala stempel secara vertikal.

**Returns:**
nilai double

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Mendapatkan nilai bool yang menunjukkan konten ditempelkan sebagai latar belakang. Jika nilai true, konten stempel diletakkan di bagian bawah. Secara default, nilai false, konten stempel diletakkan di bagian atas.

**Returns:**
nilai boolean

### put {#put-com.aspose.pdf.Page-}
Menambahkan stempel pada halaman.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Mengatur nilai bool yang menunjukkan konten ditempelkan sebagai latar belakang. Jika nilai true, konten stempel diletakkan di bagian bawah. Secara default, nilai false, konten stempel diletakkan di bagian atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Mengatur margin bawah stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Mengatur tinggi yang diinginkan dari stempel pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan horizontal stempel pada halaman.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Mengatur margin kiri stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Mengatur nilai untuk menunjukkan opasitas stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Mengatur nilai untuk menunjukkan opasitas garis tepi stempel. Nilainya dari 0.0 hingga 1.0. Secara default nilai adalah 1.0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Mengatur nilai lebar garis tepi stempel. Secara default nilai adalah 1.0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Mengatur margin kanan stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Mengatur rotasi konten stempel sesuai nilai {@code Rotation}. Catatan. Properti ini untuk mengatur sudut yang merupakan kelipatan 90 derajat (0, 90, 180, 270 derajat). Untuk mengatur sudut arbitrer gunakan properti RotateAngle. Jika sudut yang diatur oleh ArbitraryAngle bukan kelipatan 90 maka properti Rotate mengembalikan Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Mengatur sudut rotasi stempel dalam derajat. Properti ini memungkinkan mengatur sudut rotasi arbitrer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | sudut rotasi |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Mengatur Id stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai baru dari ID Stempel. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Mengatur margin atas stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mengatur perataan vertikal stempel pada halaman.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Mengatur lebar yang diinginkan dari stempel pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Atur koordinat horizontal stempel, mulai dari kiri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Atur koordinat vertikal stempel, mulai dari bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Mendapatkan faktor zoom stempel. Memungkinkan memperbesar skala stempel. Harap perhatikan bahwa pasangan properti ZoomX dan ZoomY memungkinkan mengatur faktor zoom untuk setiap sumbu secara terpisah. Pengaturan properti ini mengubah kedua properti ZoomX dan ZoomY. Jika ZoomX dan ZoomY berbeda maka properti Zoom mengembalikan nilai ZoomX.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Mengatur faktor zoom horizontal stempel. Memungkinkan memperbesar stempel secara horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Mengatur faktor zoom vertikal stempel. Memungkinkan memperbesar stempel secara vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |
