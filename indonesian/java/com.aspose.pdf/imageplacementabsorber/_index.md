---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili objek absorber dari objek penempatan gambar. Melakukan pencarian penggunaan gambar dan menyediakan akses ke hasil pencarian melalui {@code."
type: docs
weight: 2340
url: /id/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Mewakili objek absorber dari objek penempatan gambar. Melakukan pencarian penggunaan gambar dan menyediakan akses ke hasil pencarian melalui {@code ImagePlacementAbsorber.ImagePlacements} collection. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan properti penempatan gambar. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> Objek {@code ImagePlacementAbsorber} pada dasarnya digunakan dalam skenario pencarian gambar. Ketika pencarian selesai, kemunculan tersebut direpresentasikan dengan objek {@code ImagePlacement} yang terdapat dalam koleksi {@code ImagePlacementAbsorber.ImagePlacements}. Objek {@code ImagePlacement} menyediakan akses ke properti penempatan gambar: dimensi, resolusi, dll. </p> Rotasi positif gambar berlawanan arah jarum jam, untuk halaman, berarah jarum jam. Di sini, kita perlu merepresentasikan sudut rotasi gambar, sehingga kami mengurangkan sudut halaman dari sudut gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Menginisialisasi instance baru dari objek {@code ImagePlacementAbsorber}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Mendapatkan koleksi kejadian penempatan gambar yang disajikan dengan objek {@code ImagePlacement}. |
| [isReadOnlyMode](#isReadOnlyMode--) | Mendapatkan/mengatur mode hanya-baca untuk koleksi operasi parsing. Ini dapat membantu mencegah pengecualian out of memory. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Mendapatkan/mengatur mode hanya-baca untuk koleksi operasi parsing. Ini dapat membantu mencegah pengecualian out of memory. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Melakukan pencarian pada dokumen yang ditentukan. |
| [visit](#visit-com.aspose.pdf.Page-) | Melakukan pencarian pada halaman yang ditentukan. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Menginisialisasi instance baru dari objek {@code ImagePlacementAbsorber}.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Mendapatkan koleksi kejadian penempatan gambar yang disajikan dengan objek {@code ImagePlacement}.

**Returns:**
objek ImagePlacementCollection

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Mendapatkan/mengatur mode hanya-baca untuk koleksi operasi parsing. Ini dapat membantu mencegah pengecualian out of memory.

**Returns:**
nilai boolean

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Mendapatkan/mengatur mode hanya-baca untuk koleksi operasi parsing. Ini dapat membantu mencegah pengecualian out of memory.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### visit {#visit-com.aspose.pdf.IDocument-}
Melakukan pencarian pada dokumen yang ditentukan.

### visit {#visit-com.aspose.pdf.Page-}
Melakukan pencarian pada halaman yang ditentukan.
