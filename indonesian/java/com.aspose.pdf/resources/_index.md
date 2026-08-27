---
title: "Sumber Daya"
linktitle: "Sumber Daya"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang merepresentasikan sumber daya halaman."
type: docs
weight: 4220
url: /id/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Kelas yang merepresentasikan sumber daya halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Menghapus data yang di-cache, membebaskan memori, dll. |
| [getExtGStates](#getExtGStates--) | Mendapatkan semua ExGStates dari sumber daya. |
| [getFonts](#getFonts--) | Mendapatkan koleksi sumber daya {@code Fonts} |
| [getFonts](#getFonts-boolean-) | Mengembalikan koleksi font. Jika sumber daya tidak berisi entri font, maka akan dibuat tergantung pada flag CreateIfAbsent. |
| [getForms](#getForms--) | Mendapatkan koleksi {@code Forms} forms |
| [getImages](#getImages--) | Mendapatkan koleksi {@code Images} images |
| [getResourceDictionary](#getResourceDictionary--) | Bidang internal |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Mendapatkan sumber daya untuk |
| [isCommonResource](#isCommonResource--) | Benar jika sumber daya ini bersifat umum, yaitu dibagikan untuk beberapa halaman (ditempatkan dalam kamus halaman atau di setiap halaman sebagai referensi objek). Manipulasi dengan sumber daya umum harus dilakukan dengan sangat hati-hati; misalnya menghapus objek dari sumber daya umum pada satu halaman dapat menyebabkan kesalahan pada halaman lain jika objek yang dihapus digunakan pada halaman lain. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | Hanya untuk penggunaan internal! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Menghapus data yang di-cache, membebaskan memori, dll.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Mendapatkan semua ExGStates dari sumber daya.

**Returns:**
Mengembalikan kamus dengan kunci nama ExGStates.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Mendapatkan koleksi sumber daya {@code Fonts}

**Returns:**
objek FontCollection

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Mengembalikan koleksi font. Jika sumber daya tidak berisi entri font, maka akan dibuat tergantung pada flag CreateIfAbsent.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createIfAbsent |  | Jika flag ini bernilai true maka font akan dibuat jika entri ini tidak ada. |

**Returns:**
Koleksi font.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Mendapatkan koleksi {@code Forms} forms

**Returns:**
objek XFormCollection

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Mendapatkan koleksi {@code Images} images

**Returns:**
objek XImageCollection

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Bidang internal

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Mendapatkan sumber daya untuk

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Benar jika sumber daya ini bersifat umum, yaitu dibagikan untuk beberapa halaman (ditempatkan dalam kamus halaman atau di setiap halaman sebagai referensi objek). Manipulasi dengan sumber daya umum harus dilakukan dengan sangat hati-hati; misalnya menghapus objek dari sumber daya umum pada satu halaman dapat menyebabkan kesalahan pada halaman lain jika objek yang dihapus digunakan pada halaman lain.

**Returns:**
nilai boolean

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
Hanya untuk penggunaan internal!
