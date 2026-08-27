---
title: "Bookmark"
linktitle: "Bookmark"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili penanda buku."
type: docs
weight: 60
url: /id/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Mewakili penanda buku.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Bookmark](#Bookmark--) | Menginisialisasi instance baru dari kelas {@code Bookmark}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAction](#getAction--) | Mendapatkan aksi yang terikat dengan bookmark. Jika PageNumber disajikan, aksi tidak dapat ditentukan. Tipe aksi meliputi: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Mendapatkan flag tebal dari judul bookmark. |
| [getChildItem](#getChildItem--) | Mendapatkan anak-anak bookmark. Usang("Gunakan properti getChildItems() sebagai gantinya.") |
| [getChildItems](#getChildItems--) | Mendapatkan anak-anak bookmark. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Belum didukung. Nama aksi yang sesuai untuk mengeksekusi item menu di penampil Acrobat. |
| [getDestination](#getDestination--) | Mendapatkan halaman tujuan bookmark. Diperlukan jika aksi diatur sebagai "". |
| [getItalicFlag](#getItalicFlag--) | Mendapatkan flag miring dari judul bookmark. |
| [getLevel](#getLevel--) | Mendapatkan tingkat hierarki bookmark. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Mendapatkan koordinat bawah tampilan halaman. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Mendapatkan koordinat kiri tampilan halaman. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Mendapatkan koordinat kanan tampilan halaman. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Mendapatkan koordinat atas tampilan halaman. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Mendapatkan faktor zoom tampilan halaman. |
| [getPageDisplay](#getPageDisplay--) | Mendapatkan tipe halaman tujuan bookmark tampilan. |
| [getPageNumber](#getPageNumber--) | Mendapatkan nomor halaman tujuan bookmark. |
| [getRemoteFile](#getRemoteFile--) | Mendapatkan file (path) yang diperlukan untuk aksi "GoToR" bookmark. |
| [getTitle](#getTitle--) | Mendapatkan judul bookmark. |
| [getTitleColor](#getTitleColor--) | Mendapatkan warna judul bookmark. |
| [isOpen](#isOpen--) | Mendapatkan status bookmark (buka, tutup). |
| [setAction](#setAction-java.lang.String-) | Mengatur aksi yang terikat dengan bookmark. Jika PageNumber disajikan aksi tidak dapat ditentukan. Tipe aksi mencakup: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Mengatur flag tebal pada judul bookmark. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Mengatur anak-anak bookmark. Obsolete("Gunakan properti setChildItems() sebagai gantinya.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Mengatur anak-anak bookmark. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Belum didukung. Mengatur nama aksi yang sesuai untuk mengeksekusi item menu di penampil Acrobat. |
| [setDestination](#setDestination-java.lang.String-) | Mengatur halaman tujuan bookmark. Diperlukan jika aksi diatur sebagai "". |
| [setItalicFlag](#setItalicFlag-boolean-) | Mengatur flag miring pada judul bookmark. |
| [setLevel](#setLevel-int-) | Mengatur level hierarki bookmark. |
| [setOpen](#setOpen-boolean-) | Mengatur status bookmark (buka, tutup). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Mengatur koordinat bawah tampilan halaman. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Mengatur koordinat kiri tampilan halaman. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Mengatur koordinat kanan tampilan halaman. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Mengatur koordinat atas tampilan halaman. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Mengatur faktor zoom tampilan halaman. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Mengatur tipe halaman tujuan bookmark tampilan. |
| [setPageNumber](#setPageNumber-int-) | Mengatur nomor halaman tujuan bookmark. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Mengatur file (path) yang diperlukan untuk aksi "GoToR" bookmark. |
| [setTitle](#setTitle-java.lang.String-) | Mengatur judul bookmark. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Mengatur warna judul bookmark. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | konversi ke OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Menginisialisasi instance baru dari kelas {@code Bookmark}.

### getAction {#getAction--}
```
public String getAction()
```

Mendapatkan aksi yang terikat dengan bookmark. Jika PageNumber disajikan, aksi tidak dapat ditentukan. Tipe aksi meliputi: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
nilai String

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Mendapatkan flag tebal dari judul bookmark.

**Returns:**
nilai boolean

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Mendapatkan anak-anak bookmark. Usang("Gunakan properti getChildItems() sebagai gantinya.")

**Returns:**
Elemen Bookmarks

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Mendapatkan anak-anak bookmark.

**Returns:**
item anak bookmark.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Belum didukung. Nama aksi yang sesuai untuk mengeksekusi item menu di penampil Acrobat.

**Returns:**
array nilai int

### getDestination {#getDestination--}
```
public String getDestination()
```

Mendapatkan halaman tujuan bookmark. Diperlukan jika aksi diatur sebagai "".

**Returns:**
nilai String

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Mendapatkan flag miring dari judul bookmark.

**Returns:**
nilai boolean

### getLevel {#getLevel--}
```
public int getLevel()
```

Mendapatkan tingkat hierarki bookmark.

**Returns:**
nilai int

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Mendapatkan koordinat bawah tampilan halaman.

**Returns:**
nilai int

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Mendapatkan koordinat kiri tampilan halaman.

**Returns:**
nilai int

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Mendapatkan koordinat kanan tampilan halaman.

**Returns:**
nilai int

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Mendapatkan koordinat atas tampilan halaman.

**Returns:**
nilai int

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Mendapatkan faktor zoom tampilan halaman.

**Returns:**
nilai int

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Mendapatkan tipe halaman tujuan bookmark tampilan.

**Returns:**
nilai String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Mendapatkan nomor halaman tujuan bookmark.

**Returns:**
nilai int

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Mendapatkan file (path) yang diperlukan untuk aksi "GoToR" bookmark.

**Returns:**
nilai String

### getTitle {#getTitle--}
```
public String getTitle()
```

Mendapatkan judul bookmark.

**Returns:**
nilai String

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Mendapatkan warna judul bookmark.

**Returns:**
elemen Warna

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Mendapatkan status bookmark (buka, tutup).

**Returns:**
nilai boolean

### setAction {#setAction-java.lang.String-}
Mengatur aksi yang terikat dengan bookmark. Jika PageNumber disajikan aksi tidak dapat ditentukan. Tipe aksi mencakup: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Mengatur flag tebal pada judul bookmark.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Mengatur anak-anak bookmark. Obsolete("Gunakan properti setChildItems() sebagai gantinya.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Mengatur anak-anak bookmark.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Belum didukung. Mengatur nama aksi yang sesuai untuk mengeksekusi item menu di penampil Acrobat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | array nilai int |

### setDestination {#setDestination-java.lang.String-}
Mengatur halaman tujuan bookmark. Diperlukan jika aksi diatur sebagai "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Mengatur flag miring pada judul bookmark.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Mengatur level hierarki bookmark.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Mengatur status bookmark (buka, tutup).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Mengatur koordinat bawah tampilan halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Mengatur koordinat kiri tampilan halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Mengatur koordinat kanan tampilan halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Mengatur koordinat atas tampilan halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Mengatur faktor zoom tampilan halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Mengatur tipe halaman tujuan bookmark tampilan.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Mengatur nomor halaman tujuan bookmark.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Mengatur file (path) yang diperlukan untuk aksi "GoToR" bookmark.

### setTitle {#setTitle-java.lang.String-}
Mengatur judul bookmark.

### setTitleColor {#setTitleColor-java.awt.Color-}
Mengatur warna judul bookmark.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
konversi ke OutlineItemCollection
