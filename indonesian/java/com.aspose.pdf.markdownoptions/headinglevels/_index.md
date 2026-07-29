---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk bekerja dengan tingkat header berdasarkan ukuran font."
type: docs
weight: 20
url: /id/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Mewakili kelas untuk bekerja dengan tingkat header berdasarkan ukuran font.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Membuat instance baru dari kelas HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Membuat instance baru dari kelas HeadingLevels. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Menambahkan level heading. |
| [estimateLevel](#estimateLevel-double-) | Memperkirakan level header yang mungkin. Jika fontSize tidak ditemukan dalam daftar level, level yang paling dekat dengan nilai ukuran font ini akan dikembalikan. Jika fontSize berada di luar level header minimum dan maksimum yang ditentukan, metode akan mengembalikan false. |
| [findLevel](#findLevel-double-int:A-) | Menemukan level untuk ukuran font yang sesuai. Mencari kecocokan yang tepat. |
| [getAllLevels](#getAllLevels--) | Mendapatkan semua level heading. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Membuat instance baru dari kelas HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Membuat instance baru dari kelas HeadingLevels.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold |  | Nilai ambang untuk membandingkan ukuran font. Dalam ambang, level header sama. Nilai default ambang adalah 0.01. |

### addLevels {#addLevels-java.lang.Iterable-}
Menambahkan level heading.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Memperkirakan level header yang mungkin. Jika fontSize tidak ditemukan dalam daftar level, level yang paling dekat dengan nilai ukuran font ini akan dikembalikan. Jika fontSize berada di luar level header minimum dan maksimum yang ditentukan, metode akan mengembalikan false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontSize |  | Ukuran font. |

**Returns:**
Level heading.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Menemukan level untuk ukuran font yang sesuai. Mencari kecocokan yang tepat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontSize |  | Ukuran font. |
| level |  | Level heading yang sesuai untuk ukuran font yang diberikan. |

**Returns:**
False Jika fontSize tidak berada dalam rentang yang ditentukan.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Mendapatkan semua level heading.

**Returns:**
IEnumerable dari Double
