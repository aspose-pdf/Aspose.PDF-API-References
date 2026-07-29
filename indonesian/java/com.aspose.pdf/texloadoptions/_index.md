---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi untuk memuat/mengimpor file TeX ke dalam dokumen PDF."
type: docs
weight: 4870
url: /id/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Mewakili opsi untuk memuat/mengimpor file TeX ke dalam dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Membuat opsi pemuatan default untuk mengonversi file TeX menjadi dokumen PDF. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDateTime](#getDateTime--) | Mendapatkan/mengatur nilai tertentu untuk primitif tanggal/waktu seperti tahun, bulan, hari, dan waktu. |
| [getInputDirectory](#getInputDirectory--) | Mendapatkan/mengatur direktori input TeX. |
| [getJobName](#getJobName--) | Mendapatkan/mengatur nama pekerjaan. |
| [getLoadResult](#getLoadResult--) | Mendapatkan hasil untuk pemuatan dan kompilasi TeX - apakah semuanya berjalan lancar atau ada komentar/galat. |
| [getNoLigatures](#getNoLigatures--) | Mendapatkan/mengatur flag yang membatalkan ligatur di semua font. |
| [getOutputDirectory](#getOutputDirectory--) | Mendapatkan/mengatur direktori output TeX. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Mendapatkan/mengatur flag yang memungkinkan merasterkan rumus matematika. |
| [getRepeat](#getRepeat--) | Mendapatkan/mengatur flag yang menunjukkan apakah perlu menjalankan pekerjaan TeX dua kali dalam kasus, misalnya, ada referensi dalam file TeX masukan. Secara umum, perilaku ini berguna ketika mesin mengumpulkan beberapa data selama proses penataan dan menyimpannya dalam file tambahan pada run pertama. Dan pada run kedua, mesin entah bagaimana menggunakan data tersebut. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Mendapatkan/mengatur direktori input yang diperlukan TeX. Input yang diperlukan adalah file-file yang secara tertentu disertakan ke dalam file .tex utama, misalnya, paket-paket yang tidak memiliki dukungan bawaan. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Mendapatkan/mengatur flag yang menunjukkan apakah menampilkan output terminal di konsol. |
| [getSubsetFonts](#getSubsetFonts--) | Mendapatkan/mengatur flag yang menunjukkan apakah akan melakukan subset font dalam file output atau tidak. |
| [setDateTime](#setDateTime-java.util.Date-) | Mendapatkan/mengatur nilai tertentu untuk primitif tanggal/waktu seperti tahun, bulan, hari, dan waktu. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Mendapatkan/mengatur direktori input TeX. |
| [setJobName](#setJobName-java.lang.String-) | Mendapatkan/mengatur nama pekerjaan. |
| [setNoLigatures](#setNoLigatures-boolean-) | Mendapatkan/mengatur flag yang membatalkan ligatur di semua font. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Mendapatkan/mengatur direktori output TeX. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Mendapatkan/mengatur flag yang memungkinkan merasterkan rumus matematika. |
| [setRepeat](#setRepeat-boolean-) | Mendapatkan/mengatur flag yang menunjukkan apakah perlu menjalankan pekerjaan TeX dua kali dalam kasus, misalnya, ada referensi dalam file TeX masukan. Secara umum, perilaku ini berguna ketika mesin mengumpulkan beberapa data selama proses penataan dan menyimpannya dalam file tambahan pada run pertama. Dan pada run kedua, mesin entah bagaimana menggunakan data tersebut. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Mendapatkan/mengatur direktori input yang diperlukan TeX. Input yang diperlukan adalah file-file yang secara tertentu disertakan ke dalam file .tex utama, misalnya, paket-paket yang tidak memiliki dukungan bawaan. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Mendapatkan/mengatur flag yang menunjukkan apakah menampilkan output terminal di konsol. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Mendapatkan/mengatur flag yang menunjukkan apakah akan melakukan subset font dalam file output atau tidak. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Membuat opsi pemuatan default untuk mengonversi file TeX menjadi dokumen PDF.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Mendapatkan/mengatur nilai tertentu untuk primitif tanggal/waktu seperti tahun, bulan, hari, dan waktu.

**Returns:**
Instansi Date

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Mendapatkan/mengatur direktori input TeX.

**Returns:**
Instance ITeXInputDirectory

### getJobName {#getJobName--}
```
public final String getJobName()
```

Mendapatkan/mengatur nama pekerjaan.

**Returns:**
nilai String

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Mendapatkan hasil untuk pemuatan dan kompilasi TeX - apakah semuanya berjalan lancar atau ada komentar/galat.

**Returns:**
Elemen TeXLoadResult

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Mendapatkan/mengatur flag yang membatalkan ligatur di semua font.

**Returns:**
nilai boolean

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Mendapatkan/mengatur direktori output TeX.

**Returns:**
Instance ITeXOutputDirectory

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Mendapatkan/mengatur flag yang memungkinkan merasterkan rumus matematika.

**Returns:**
nilai boolean

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Mendapatkan/mengatur flag yang menunjukkan apakah perlu menjalankan pekerjaan TeX dua kali dalam kasus, misalnya, ada referensi dalam file TeX masukan. Secara umum, perilaku ini berguna ketika mesin mengumpulkan beberapa data selama proses penataan dan menyimpannya dalam file tambahan pada run pertama. Dan pada run kedua, mesin entah bagaimana menggunakan data tersebut.

**Returns:**
nilai boolean

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Mendapatkan/mengatur direktori input yang diperlukan TeX. Input yang diperlukan adalah file-file yang secara tertentu disertakan ke dalam file .tex utama, misalnya, paket-paket yang tidak memiliki dukungan bawaan.

**Returns:**
Instance ITeXInputDirectory

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Mendapatkan/mengatur flag yang menunjukkan apakah menampilkan output terminal di konsol.

**Returns:**
nilai boolean

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Mendapatkan/mengatur flag yang menunjukkan apakah akan melakukan subset font dalam file output atau tidak.

**Returns:**
nilai boolean

### setDateTime {#setDateTime-java.util.Date-}
Mendapatkan/mengatur nilai tertentu untuk primitif tanggal/waktu seperti tahun, bulan, hari, dan waktu.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Mendapatkan/mengatur direktori input TeX.

### setJobName {#setJobName-java.lang.String-}
Mendapatkan/mengatur nama pekerjaan.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Mendapatkan/mengatur flag yang membatalkan ligatur di semua font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Mendapatkan/mengatur direktori output TeX.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Mendapatkan/mengatur flag yang memungkinkan merasterkan rumus matematika.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Mendapatkan/mengatur flag yang menunjukkan apakah perlu menjalankan pekerjaan TeX dua kali dalam kasus, misalnya, ada referensi dalam file TeX masukan. Secara umum, perilaku ini berguna ketika mesin mengumpulkan beberapa data selama proses penataan dan menyimpannya dalam file tambahan pada run pertama. Dan pada run kedua, mesin entah bagaimana menggunakan data tersebut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Mendapatkan/mengatur direktori input yang diperlukan TeX. Input yang diperlukan adalah file-file yang secara tertentu disertakan ke dalam file .tex utama, misalnya, paket-paket yang tidak memiliki dukungan bawaan.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Mendapatkan/mengatur flag yang menunjukkan apakah menampilkan output terminal di konsol.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Mendapatkan/mengatur flag yang menunjukkan apakah akan melakukan subset font dalam file output atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
