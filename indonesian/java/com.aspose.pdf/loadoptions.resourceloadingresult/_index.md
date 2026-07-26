---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Hasil pemuatan khusus sumber daya."
type: docs
weight: 2820
url: /id/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Hasil pemuatan khusus sumber daya.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Membuat instance dari hasil pemuatan |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getData](#getData--) | Data biner yang dimuat dengan pemuat khusus - harus disetel setelah pemuatan |
| [getEncodingIfKnown](#getEncodingIfKnown--) | Kadang-kadang encoding sumber diketahui setelah atau selama pemuatan. Dalam kasus seperti itu kode khusus dapat memberikan pengetahuan tersebut kepada konverter melalui parameter ini. Anda dapat membiarkan null pada parameter ini jika encoding tidak diketahui atau tidak penting. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | Kadang-kadang tidak mungkin memuat sumber yang diminta karena suatu alasan. Ketidaktersediaan sumber sering tidak menyebabkan kegagalan konversi dan dokumen hasil tetap dapat dibuat (meskipun mungkin dengan kualitas sedikit lebih buruk, tanpa gambar, dll.). Jika pengecualian terjadi selama pemuatan, cukup tangkap dan masukkan ke dalam parameter ini - kadang-kadang informasi tersebut berguna bagi konverter untuk merender hasil. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | Kadang-kadang pengetahuan tentang tipe MIME dari sumber yang dimuat berguna bagi konverter. Anda dapat menyediakan tipe MIME (jika diketahui setelah pemuatan) dalam parameter ini. Harap biarkan parameter bernilai null ketika tipe MIME tidak diketahui atau tidak perlu disediakan. |
| [isLoadingCancelled](#isLoadingCancelled--) | Kadang-kadang karena beberapa alasan pemuatan tidak boleh terjadi dengan kode khusus. Dalam kasus tersebut, harap setel flag ini menjadi True. Dengan begitu konverter akan mencoba menggunakan pemuat sumber daya default internal untuk mendapatkan hasil tersebut (seperti perilakunya ketika strategi khusus tidak disediakan). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | Kadang-kadang encoding sumber diketahui setelah atau selama pemuatan. Dalam kasus seperti itu kode khusus dapat memberikan pengetahuan tersebut kepada konverter melalui parameter ini. Anda dapat membiarkan null pada parameter ini jika encoding tidak diketahui atau tidak penting. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Kadang-kadang tidak mungkin memuat sumber yang diminta karena suatu alasan. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | Kadang-kadang karena beberapa alasan pemuatan tidak boleh terjadi dengan kode khusus. Dalam kasus tersebut, harap setel flag ini menjadi True. Dengan begitu konverter akan mencoba menggunakan pemuat sumber daya default internal untuk mendapatkan hasil tersebut (seperti perilakunya ketika strategi khusus tidak disediakan). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | Kadang-kadang pengetahuan tentang tipe MIME dari sumber yang dimuat berguna bagi konverter. Anda dapat menyediakan tipe MIME (jika diketahui setelah pemuatan) dalam parameter ini. Harap biarkan parameter bernilai null ketika tipe MIME tidak diketahui atau tidak perlu disediakan. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Membuat instance dari hasil pemuatan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data |  | hasil pemuatan khusus harus selalu disediakan, dapat berupa array dengan panjang nol jika tidak mungkin mendapatkan hasil apa pun |

### getData {#getData--}
```
public byte[] getData()
```

Data biner yang dimuat dengan pemuat khusus - harus disetel setelah pemuatan

**Returns:**
array nilai byte

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

Kadang-kadang encoding sumber diketahui setelah atau selama pemuatan. Dalam kasus seperti itu kode khusus dapat memberikan pengetahuan tersebut kepada konverter melalui parameter ini. Anda dapat membiarkan null pada parameter ini jika encoding tidak diketahui atau tidak penting.

**Returns:**
Instansi Charset

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

Kadang-kadang tidak mungkin memuat sumber yang diminta karena suatu alasan. Ketidaktersediaan sumber sering tidak menyebabkan kegagalan konversi dan dokumen hasil tetap dapat dibuat (meskipun mungkin dengan kualitas sedikit lebih buruk, tanpa gambar, dll.). Jika pengecualian terjadi selama pemuatan, cukup tangkap dan masukkan ke dalam parameter ini - kadang-kadang informasi tersebut berguna bagi konverter untuk merender hasil.

**Returns:**
Pengecualian

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

Kadang-kadang pengetahuan tentang tipe MIME dari sumber yang dimuat berguna bagi konverter. Anda dapat menyediakan tipe MIME (jika diketahui setelah pemuatan) dalam parameter ini. Harap biarkan parameter bernilai null ketika tipe MIME tidak diketahui atau tidak perlu disediakan.

**Returns:**
nilai String

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

Kadang-kadang karena beberapa alasan pemuatan tidak boleh terjadi dengan kode khusus. Dalam kasus tersebut, harap setel flag ini menjadi True. Dengan begitu konverter akan mencoba menggunakan pemuat sumber daya default internal untuk mendapatkan hasil tersebut (seperti perilakunya ketika strategi khusus tidak disediakan).

**Returns:**
nilai boolean

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
Kadang-kadang encoding sumber diketahui setelah atau selama pemuatan. Dalam kasus seperti itu kode khusus dapat memberikan pengetahuan tersebut kepada konverter melalui parameter ini. Anda dapat membiarkan null pada parameter ini jika encoding tidak diketahui atau tidak penting.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
Kadang-kadang tidak mungkin memuat sumber yang diminta karena suatu alasan.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

Kadang-kadang karena beberapa alasan pemuatan tidak boleh terjadi dengan kode khusus. Dalam kasus tersebut, harap setel flag ini menjadi True. Dengan begitu konverter akan mencoba menggunakan pemuat sumber daya default internal untuk mendapatkan hasil tersebut (seperti perilakunya ketika strategi khusus tidak disediakan).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| loadingCancelled |  | nilai boolean |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
Kadang-kadang pengetahuan tentang tipe MIME dari sumber yang dimuat berguna bagi konverter. Anda dapat menyediakan tipe MIME (jika diketahui setelah pemuatan) dalam parameter ini. Harap biarkan parameter bernilai null ketika tipe MIME tidak diketahui atau tidak perlu disediakan.
