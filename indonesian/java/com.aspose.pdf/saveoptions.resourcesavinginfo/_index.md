---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file sumber eksternal yang terjadi selama konversi PDF ke format lain (mis. HTML)."
type: docs
weight: 4440
url: /id/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file sumber eksternal yang terjadi selama konversi PDF ke format lain (mis. HTML).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContentStream](#getContentStream--) | Ditetapkan oleh konverter. Mewakili konten biner dari file yang disimpan. |
| [getResourceType](#getResourceType--) | Ditetapkan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode khusus dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau ke mana menyimpan file tersebut. |
| [getSupposedFileName](#getSupposedFileName--) | Ditetapkan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode khusus dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau ke mana menyimpan file tersebut. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | bendera ini harus disetel ke "true" dalam kode khusus jika karena alasan tertentu file yang diusulkan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturannya disetel ke true berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri (dalam kedua konteks - untuk menyimpan di suatu tempat dan untuk penamaan file yang dirujuk). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | bendera ini harus disetel ke "true" dalam kode khusus jika karena alasan tertentu file yang diusulkan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturannya disetel ke true berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri (dalam kedua konteks - untuk menyimpan di suatu tempat dan untuk penamaan file yang dirujuk). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Ditetapkan oleh konverter. Mewakili konten biner dari file yang disimpan.

**Returns:**
array byte

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Ditetapkan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode khusus dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau ke mana menyimpan file tersebut.

**Returns:**
Elemen NodeLevelResourceType @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Ditetapkan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode khusus dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau ke mana menyimpan file tersebut.

**Returns:**
nilai String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

bendera ini harus disetel ke "true" dalam kode khusus jika karena alasan tertentu file yang diusulkan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturannya disetel ke true berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri (dalam kedua konteks - untuk menyimpan di suatu tempat dan untuk penamaan file yang dirujuk).

**Returns:**
nilai boolean

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

bendera ini harus disetel ke "true" dalam kode khusus jika karena alasan tertentu file yang diusulkan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturannya disetel ke true berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri (dalam kedua konteks - untuk menyimpan di suatu tempat dan untuk penamaan file yang dirujuk).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| customProcessingCancelled |  | nilai boolean |
