---
title: "Image"
linktitle: "Image"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili gambar."
type: docs
weight: 2280
url: /id/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Mewakili gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Image](#Image--) | konstruktor default |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Coba mengonversi ke aliran dengan gambar bmp/png/gif/tiff menjadi aliran dengan gambar format JPG. |
| [deepClone](#deepClone--) | Klon gambar. |
| [getBitmapInfo](#getBitmapInfo--) | Mendapatkan atau mengatur byte gambar yang tidak terkompresi. |
| [getBitmapSize](#getBitmapSize--) | Mendapatkan ukuran bitmap gambar. |
| [getBufferedImage](#getBufferedImage--) | Mendapatkan gambar java awt. |
| [getFile](#getFile--) | Mendapatkan file gambar. |
| [getFileType](#getFileType--) | Mendapatkan tipe file gambar. |
| [getFixHeight](#getFixHeight--) | Mendapatkan tinggi gambar. |
| [getFixWidth](#getFixWidth--) | Mendapatkan lebar gambar. |
| [getImageScale](#getImageScale--) | Mendapatkan skala gambar. |
| [getImageStream](#getImageStream--) | Mendapatkan aliran gambar. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Mengembalikan tipe mime untuk gambar. |
| [getTitle](#getTitle--) | Mendapatkan nilai string yang menunjukkan judul gambar. |
| [isApplyResolution](#isApplyResolution--) | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah gambar menggunakan resolusi selama pembuatan |
| [isBlackWhite](#isBlackWhite--) | Mendapatkan nilai boolean yang menunjukkan apakah gambar dipaksa menjadi hitam-putih. Jika gambar TIFF dengan subformat CCITT digunakan, properti ini harus diatur ke true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Coba deteksi dan gunakan enkoding 1bpp untuk gambar skala abu-abu Nilai default == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah gambar menggunakan resolusi selama pembuatan |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Mendapatkan atau mengatur byte gambar yang tidak terkompresi. |
| [setBlackWhite](#setBlackWhite-boolean-) | Mengatur nilai boolean yang menunjukkan apakah gambar dipaksa menjadi hitam-putih. Jika gambar TIFF dengan subformat CCITT digunakan, properti ini harus diatur ke true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Coba deteksi dan gunakan enkoding 1bpp untuk gambar skala abu-abu. Nilai default == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Mengatur gambar java awt. |
| [setFile](#setFile-java.lang.String-) | Mengatur file gambar. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Mengatur tipe file gambar. |
| [setFixHeight](#setFixHeight-double-) | Mengatur tinggi gambar. |
| [setFixWidth](#setFixWidth-double-) | Mengatur lebar gambar. |
| [setImageScale](#setImageScale-double-) | Mengatur skala gambar. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Mengatur aliran gambar. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Mengatur nilai string yang menunjukkan judul gambar. |

### Image {#Image--}
```
public Image()
```

konstruktor default

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Coba mengonversi ke aliran dengan gambar bmp/png/gif/tiff menjadi aliran dengan gambar format JPG.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klon gambar.

**Returns:**
Objek yang diklon.

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Mendapatkan atau mengatur byte gambar yang tidak terkompresi.

**Returns:**
Instansi BitmapInfo

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Mendapatkan ukuran bitmap gambar.

**Returns:**
Instansi Rectangle

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Mendapatkan gambar java awt.

**Returns:**
Objek BufferedImage

### getFile {#getFile--}
```
public String getFile()
```

Mendapatkan file gambar.

**Returns:**
nilai String

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Mendapatkan tipe file gambar.

**Returns:**
nilai int @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Mendapatkan tinggi gambar.

**Returns:**
nilai double

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Mendapatkan lebar gambar.

**Returns:**
nilai double

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Mendapatkan skala gambar.

**Returns:**
nilai double

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Mendapatkan aliran gambar.

**Returns:**
Objek InputStream

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Mengembalikan tipe mime untuk gambar.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Mendapatkan nilai string yang menunjukkan judul gambar.

**Returns:**
nilai TextFragment

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah gambar menggunakan resolusi selama pembuatan

**Returns:**
nilai boolean

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Mendapatkan nilai boolean yang menunjukkan apakah gambar dipaksa menjadi hitam-putih. Jika gambar TIFF dengan subformat CCITT digunakan, properti ini harus diatur ke true.

**Returns:**
nilai boolean

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Coba deteksi dan gunakan enkoding 1bpp untuk gambar skala abu-abu Nilai default == FALSE

**Returns:**
nilai boolean

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah gambar menggunakan resolusi selama pembuatan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Mendapatkan atau mengatur byte gambar yang tidak terkompresi.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Mengatur nilai boolean yang menunjukkan apakah gambar dipaksa menjadi hitam-putih. Jika gambar TIFF dengan subformat CCITT digunakan, properti ini harus diatur ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Coba deteksi dan gunakan enkoding 1bpp untuk gambar skala abu-abu. Nilai default == FALSE

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| blackWhiteForGrayScale |  | nilai boolean |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Mengatur gambar java awt.

### setFile {#setFile-java.lang.String-}
Mengatur file gambar.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Mengatur tipe file gambar.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Mengatur tinggi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Mengatur lebar gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Mengatur skala gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setImageStream {#setImageStream-java.io.InputStream-}
Mengatur aliran gambar.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Mengatur nilai string yang menunjukkan judul gambar.
