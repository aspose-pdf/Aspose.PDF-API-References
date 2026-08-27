---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber daya eksternal selama konversi PDF ke HTML."
type: docs
weight: 2070
url: /id/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber daya eksternal selama konversi PDF ke HTML.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | membuat instance baru dari HtmlImageSavingInfo |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Memberitahu kode khusus pada halaman mana dari kumpulan file halaman HTML yang dihasilkan gambar yang disimpan terkait. Jika pemisahan halaman dimatikan, nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML yang dihasilkan. |
| [getImageType](#getImageType--) | Mewakili tipe gambar yang disimpan yang direferensikan dalam HTML. Ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan. |
| [getParentType](#getParentType--) | Gambar yang disimpan dapat terkait dengan HTML itu sendiri atau dapat diekstrak dari SVG yang disematkan ke HTML. Properti ini dapat memberi tahu kode khusus tipe induk dari gambar yang diproses. Properti ini ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan dengan gambar tersebut (misalnya kode khusus dapat menentukan di mana menyimpan gambar atau bagaimana gambar harus direferensikan dalam konten induk). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Memberitahu kode khusus pada halaman mana dari dokumen PDF asli gambar yang disimpan terkait. Karena mungkin tidak semua halaman dokumen asli akan disimpan, nilai ini memberi tahu nomor halaman host dalam PDF asli. Jika nomor halaman asli karena alasan tertentu tidak diketahui, selalu mengembalikan '1'. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Memberitahu kode khusus pada halaman mana dari kumpulan file halaman HTML yang dihasilkan gambar yang disimpan terkait. Jika pemisahan halaman dimatikan, nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML yang dihasilkan. |
| [setImageType](#setImageType-int-) | Mewakili tipe gambar yang disimpan yang direferensikan dalam HTML. Ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan. |
| [setParentType](#setParentType-int-) | Gambar yang disimpan dapat terkait dengan HTML itu sendiri atau dapat diekstrak dari SVG yang disematkan ke HTML. Properti ini dapat memberi tahu kode khusus tipe induk dari gambar yang diproses. Properti ini ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan dengan gambar tersebut (misalnya kode khusus dapat menentukan di mana menyimpan gambar atau bagaimana gambar harus direferensikan dalam konten induk). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Memberitahu kode khusus pada halaman mana dari dokumen PDF asli gambar yang disimpan terkait. Karena mungkin tidak semua halaman dokumen asli akan disimpan, nilai ini memberi tahu nomor halaman host dalam PDF asli. Jika nomor halaman asli karena alasan tertentu tidak diketahui, selalu mengembalikan '1'. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

membuat instance baru dari HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Memberitahu kode khusus pada halaman mana dari kumpulan file halaman HTML yang dihasilkan gambar yang disimpan terkait. Jika pemisahan halaman dimatikan, nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML yang dihasilkan.

**Returns:**
nilai int

### getImageType {#getImageType--}
```
public int getImageType()
```

Mewakili tipe gambar yang disimpan yang direferensikan dalam HTML. Ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan.

**Returns:**
Elemen HtmlImageType @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

Gambar yang disimpan dapat terkait dengan HTML itu sendiri atau dapat diekstrak dari SVG yang disematkan ke HTML. Properti ini dapat memberi tahu kode khusus tipe induk dari gambar yang diproses. Properti ini ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan dengan gambar tersebut (misalnya kode khusus dapat menentukan di mana menyimpan gambar atau bagaimana gambar harus direferensikan dalam konten induk).

**Returns:**
Elemen ImageParentTypes @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Memberitahu kode khusus pada halaman mana dari dokumen PDF asli gambar yang disimpan terkait. Karena mungkin tidak semua halaman dokumen asli akan disimpan, nilai ini memberi tahu nomor halaman host dalam PDF asli. Jika nomor halaman asli karena alasan tertentu tidak diketahui, selalu mengembalikan '1'.

**Returns:**
nilai int

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Memberitahu kode khusus pada halaman mana dari kumpulan file halaman HTML yang dihasilkan gambar yang disimpan terkait. Jika pemisahan halaman dimatikan, nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML yang dihasilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlHostPageNumber |  | nilai int |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Mewakili tipe gambar yang disimpan yang direferensikan dalam HTML. Ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageType |  | Elemen HtmlImageType @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

Gambar yang disimpan dapat terkait dengan HTML itu sendiri atau dapat diekstrak dari SVG yang disematkan ke HTML. Properti ini dapat memberi tahu kode khusus tipe induk dari gambar yang diproses. Properti ini ditetapkan oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan dengan gambar tersebut (misalnya kode khusus dapat menentukan di mana menyimpan gambar atau bagaimana gambar harus direferensikan dalam konten induk).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parentType |  | Elemen ImageParentTypes @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Memberitahu kode khusus pada halaman mana dari dokumen PDF asli gambar yang disimpan terkait. Karena mungkin tidak semua halaman dokumen asli akan disimpan, nilai ini memberi tahu nomor halaman host dalam PDF asli. Jika nomor halaman asli karena alasan tertentu tidak diketahui, selalu mengembalikan '1'.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfHostPageNumber |  | nilai int |
