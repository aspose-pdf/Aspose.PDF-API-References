---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Jika properti SplitToPages dari HtmlSaveOptions diaktifkan, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama konversi PDF ke HTML. Kelas ini mewakili sekumpulan."
type: docs
weight: 2100
url: /id/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

Jika properti SplitToPages dari HtmlSaveOptions diaktifkan, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama konversi PDF ke HTML. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan khusus markup satu halaman HTML selama konversi PDF ke HTML

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContentStream](#getContentStream--) | Ditentukan oleh konverter. Mewakili HTML yang disimpan sebagai aliran. |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini berisi urutan file halaman HTML yang disimpan. Properti ini dapat digunakan dalam logika kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan halaman HTML, dan jika pemisahan per halaman dimatikan nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML besar yang dihasilkan untuk seluruh dokumen sumber. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini memberi tahu kode khusus dari halaman PDF asli mana markup HTML yang disimpan dibuat. Jika nomor halaman asli karena suatu alasan tidak diketahui atau SplitToPages=false, maka properti ini selalu berisi '0' yang menandakan bahwa konverter tidak dapat menyediakan nomor halaman PDF asli yang tepat untuk file markup HTML yang diberikan. |
| [getSupposedFileName](#getSupposedFileName--) | Ditentukan oleh konverter. Nama file yang diharapkan yang dikirim dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan konten. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Harus diatur dalam kode khusus bila diperlukan. Bendera ini harus diset ke "true" dalam kode khusus jika karena alasan tertentu markup HTML yang diberikan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar konverter. Jadi, mengatur bendera ini dalam kode khusus berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Ditentukan oleh konverter. Mewakili HTML yang disimpan sebagai aliran. |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Harus diatur dalam kode khusus bila diperlukan. Bendera ini harus diset ke "true" dalam kode khusus jika karena alasan tertentu markup HTML yang diberikan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar konverter. Jadi, mengatur bendera ini dalam kode khusus berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini berisi urutan file halaman HTML yang disimpan. Properti ini dapat digunakan dalam logika kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan halaman HTML, dan jika pemisahan per halaman dimatikan nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML besar yang dihasilkan untuk seluruh dokumen sumber. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini memberi tahu kode khusus dari halaman PDF asli mana markup HTML yang disimpan dibuat. Jika nomor halaman asli karena suatu alasan tidak diketahui atau SplitToPages=false, maka properti ini selalu berisi '0' yang menandakan bahwa konverter tidak dapat menyediakan nomor halaman PDF asli yang tepat untuk file markup HTML yang diberikan. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Ditentukan oleh konverter. Nama file yang diharapkan yang dikirim dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan konten. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Ditentukan oleh konverter. Mewakili HTML yang disimpan sebagai aliran.

**Returns:**
Instansi InputStream

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini berisi urutan file halaman HTML yang disimpan. Properti ini dapat digunakan dalam logika kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan halaman HTML, dan jika pemisahan per halaman dimatikan nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML besar yang dihasilkan untuk seluruh dokumen sumber.

**Returns:**
nilai int

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini memberi tahu kode khusus dari halaman PDF asli mana markup HTML yang disimpan dibuat. Jika nomor halaman asli karena suatu alasan tidak diketahui atau SplitToPages=false, maka properti ini selalu berisi '0' yang menandakan bahwa konverter tidak dapat menyediakan nomor halaman PDF asli yang tepat untuk file markup HTML yang diberikan.

**Returns:**
nilai int

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Ditentukan oleh konverter. Nama file yang diharapkan yang dikirim dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan konten.

**Returns:**
nilai String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Harus diatur dalam kode khusus bila diperlukan. Bendera ini harus diset ke "true" dalam kode khusus jika karena alasan tertentu markup HTML yang diberikan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar konverter. Jadi, mengatur bendera ini dalam kode khusus berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri.

**Returns:**
nilai boolean

### setContentStream {#setContentStream-java.io.InputStream-}
Ditentukan oleh konverter. Mewakili HTML yang disimpan sebagai aliran.

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Harus diatur dalam kode khusus bila diperlukan. Bendera ini harus diset ke "true" dalam kode khusus jika karena alasan tertentu markup HTML yang diberikan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar konverter. Jadi, mengatur bendera ini dalam kode khusus berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| customProcessingCancelled |  | nilai boolean |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini berisi urutan file halaman HTML yang disimpan. Properti ini dapat digunakan dalam logika kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan halaman HTML, dan jika pemisahan per halaman dimatikan nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML besar yang dihasilkan untuk seluruh dokumen sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlHostPageNumber |  | nilai int |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini memberi tahu kode khusus dari halaman PDF asli mana markup HTML yang disimpan dibuat. Jika nomor halaman asli karena suatu alasan tidak diketahui atau SplitToPages=false, maka properti ini selalu berisi '0' yang menandakan bahwa konverter tidak dapat menyediakan nomor halaman PDF asli yang tepat untuk file markup HTML yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfHostPageNumber |  | nilai int |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Ditentukan oleh konverter. Nama file yang diharapkan yang dikirim dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan konten.
