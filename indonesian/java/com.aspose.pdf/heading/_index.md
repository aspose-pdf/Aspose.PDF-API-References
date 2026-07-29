---
title: "Judul"
linktitle: "Judul"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili judul."
type: docs
weight: 1890
url: /id/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Mewakili judul.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Heading](#Heading--) | Hanya untuk penggunaan internal |
| [Heading](#Heading-int-) | Menginisialisasi instance baru dari kelas Cell. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Menggandakan judul dengan semua segmen. |
| [deepClone](#deepClone--) | Menggandakan judul. |
| [getDestinationPage](#getDestinationPage--) | Mendapatkan halaman tujuan. |
| [getLevel](#getLevel--) | Mendapatkan level. |
| [getStartNumber](#getStartNumber--) | Mendapatkan nomor awal judul. |
| [getStyle](#getStyle--) | Mendapatkan atau mengatur gaya. |
| [getTocPage](#getTocPage--) | Mendapatkan halaman yang berisi judul ini. |
| [getTop](#getTop--) | Mendapatkan nilai Y atas dari judul ini (untuk penggunaan internal). |
| [getUserLabel](#getUserLabel--) | Mendapatkan atau mengatur label pengguna. |
| [isAutoSequence](#isAutoSequence--) | Mendapatkan apakah judul harus diberi nomor secara otomatis. |
| [isInList](#isInList--) | Mendapatkan apakah judul harus berada dalam daftar toc. |
| [setAutoSequence](#setAutoSequence-boolean-) | mengatur agar judul diberi nomor secara otomatis. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | mengatur halaman tujuan. |
| [setInList](#setInList-boolean-) | mengatur agar judul berada dalam daftar toc. |
| [setLevel](#setLevel-int-) | mengatur tingkat. |
| [setStartNumber](#setStartNumber-int-) | Mendapatkan nomor awal heading. Nilai: The startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | mengatur atau mengatur gaya. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Mengatur halaman yang berisi heading ini. |
| [setTop](#setTop-double-) | mengatur nilai Y atas dari heading ini (untuk penggunaan internal). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Mendapatkan atau mengatur label pengguna. |

### Heading {#Heading--}
```
public Heading()
```

Hanya untuk penggunaan internal

### Heading {#Heading-int-}
```
public Heading(int level)
```

Menginisialisasi instance baru dari kelas Cell.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| level |  | Level heading. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Menggandakan judul dengan semua segmen.

**Returns:**
Objek yang diklon.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Menggandakan judul.

**Returns:**
Objek yang diklon.

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Mendapatkan halaman tujuan.

**Returns:**
Halaman tujuan.

### getLevel {#getLevel--}
```
public int getLevel()
```

Mendapatkan level.

**Returns:**
Level heading.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Mendapatkan nomor awal judul.

**Returns:**
Nilai: The startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Mendapatkan atau mengatur gaya.

**Returns:**
Gaya heading.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Mendapatkan halaman yang berisi judul ini.

**Returns:**
Halaman.

### getTop {#getTop--}
```
public double getTop()
```

Mendapatkan nilai Y atas dari judul ini (untuk penggunaan internal).

**Returns:**
Nilai Y atas

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Mendapatkan atau mengatur label pengguna.

**Returns:**
objek TextSegment

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Mendapatkan apakah judul harus diberi nomor secara otomatis.

**Returns:**
IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Mendapatkan apakah judul harus berada dalam daftar toc.

**Returns:**
IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

mengatur agar judul diberi nomor secara otomatis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
mengatur halaman tujuan.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

mengatur agar judul berada dalam daftar toc.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

mengatur tingkat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Level heading. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Mendapatkan nomor awal heading. Nilai: The startNumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
mengatur atau mengatur gaya.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Mengatur halaman yang berisi heading ini.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

mengatur nilai Y atas dari heading ini (untuk penggunaan internal).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai Y atas |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Mendapatkan atau mengatur label pengguna.
