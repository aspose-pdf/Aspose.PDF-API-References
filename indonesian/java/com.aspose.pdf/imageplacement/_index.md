---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili karakteristik sebuah gambar yang ditempatkan pada halaman dokumen Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan gambar.</pre>"
type: docs
weight: 2330
url: /id/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> Mewakili karakteristik sebuah gambar yang ditempatkan pada halaman dokumen Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan gambar sebagai bitmap dengan dimensi yang terlihat. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Ketika sebuah gambar ditempatkan pada halaman, gambar tersebut dapat memiliki dimensi yang berbeda dari dimensi fisik yang didefinisikan dalam {@code Resources}. Objek {@code ImagePlacement} dimaksudkan untuk menyediakan informasi tersebut seperti dimensi, resolusi, dan sebagainya. </p>

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Mendapatkan parameter komposit dari keadaan grafik yang aktif untuk gambar yang ditempatkan pada halaman. |
| [getImage](#getImage--) | Mendapatkan objek sumber daya XImage yang terkait. |
| [getMatrix](#getMatrix--) | Matriks transformasi saat ini untuk gambar ini. |
| [getOperator](#getOperator--) | Operator yang digunakan untuk menampilkan gambar. |
| [getPage](#getPage--) | Mendapatkan halaman yang berisi gambar. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang gambar. |
| [getResolution](#getResolution--) | Mendapatkan resolusi gambar. |
| [getRotation](#getRotation--) | Mendapatkan sudut rotasi gambar. |
| [hide](#hide--) | Hapus gambar dari halaman. |
| [replace](#replace-java.io.InputStream-) | Ganti gambar dalam koleksi dengan gambar lain. |
| [save](#save-java.io.OutputStream-) | Menyimpan gambar dengan transformasi yang sesuai: skala, rotasi, dan resolusi. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Menyimpan gambar dengan transformasi yang sesuai: skala, rotasi, dan resolusi. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Mendapatkan parameter komposit dari keadaan grafik yang aktif untuk gambar yang ditempatkan pada halaman.

**Returns:**
Objek CompositingParameters

### getImage {#getImage--}
```
public XImage getImage()
```

Mendapatkan objek sumber daya XImage yang terkait.

**Returns:**
objek XImage

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matriks transformasi saat ini untuk gambar ini.

**Returns:**
Objek Matrix

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Operator yang digunakan untuk menampilkan gambar.

**Returns:**
Instansi Operator

### getPage {#getPage--}
```
public Page getPage()
```

Mendapatkan halaman yang berisi gambar.

**Returns:**
objek Page

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang gambar.

**Returns:**
objek Rectangle

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Mendapatkan resolusi gambar.

**Returns:**
Objek Resolution

### getRotation {#getRotation--}
```
public float getRotation()
```

Mendapatkan sudut rotasi gambar.

**Returns:**
nilai int

### hide {#hide--}
```
public final void hide()
```

Hapus gambar dari halaman.

### replace {#replace-java.io.InputStream-}
Ganti gambar dalam koleksi dengan gambar lain.

### save {#save-java.io.OutputStream-}
Menyimpan gambar dengan transformasi yang sesuai: skala, rotasi, dan resolusi.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Menyimpan gambar dengan transformasi yang sesuai: skala, rotasi, dan resolusi.
