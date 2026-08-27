---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Tipe SaveOptions menyimpan tingkat abstraksi pada opsi penyimpanan individu"
type: docs
weight: 4370
url: /id/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

Tipe SaveOptions menyimpan tingkat abstraksi pada opsi penyimpanan individu

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Format penyimpanan data. |
| [getWarningHandler](#getWarningHandler--) | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort, dalam hal ini operasi Save harus dihentikan. |
| [isCacheGlyphs](#isCacheGlyphs--) | Menampilkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman APS. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [isCloseResponse](#isCloseResponse--) | Mendapatkan nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Menampilkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman APS. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [setCloseResponse](#setCloseResponse-boolean-) | Mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort, dalam hal ini operasi Save harus dihentikan. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Format penyimpanan data.

**Returns:**
Nilai SaveFormat @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort, dalam hal ini operasi Save harus dihentikan.

**Returns:**
Nilai IWarningCallback

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Menampilkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman APS. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori.

**Returns:**
nilai boolean

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Mendapatkan nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons.

**Returns:**
nilai boolean

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Menampilkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman APS. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort, dalam hal ini operasi Save harus dihentikan.
