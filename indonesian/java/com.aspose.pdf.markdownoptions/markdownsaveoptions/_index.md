---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas opsi penyimpanan dokumen dalam format markdown."
type: docs
weight: 60
url: /id/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Mewakili kelas opsi penyimpanan dokumen dalam format markdown.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Membuat opsi instance untuk menyimpan dokumen dalam format markdown. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Dapatkan atau atur area persegi panjang untuk mengekstrak konten ke markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Mendapatkan atau mengatur gaya penekanan untuk dokumen yang dihasilkan. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Mendapatkan dan mengatur properti yang menunjukkan apakah grafik vektor harus diekstrak. |
| [getHeadingLevels](#getHeadingLevels--) | Mendefinisikan tingkat heading yang diharapkan untuk digunakan dalam strategi pengenalan header FontSize. Jika nilai properti ini diatur, maka strategi pengenalan header {@link HeadingRecognitionStrategy#Heuristic} akan dipilih ketika strategi {@link HeadingRecognitionStrategy#Auto} diatur meskipun dokumen berisi bookmark. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Mendapatkan atau mengatur strategi pengenalan heading. |
| [getHeadingStyle](#getHeadingStyle--) | Mendapatkan atau mengatur gaya heading untuk dokumen yang dihasilkan. |
| [getLineBreakStyle](#getLineBreakStyle--) | Mendapatkan atau mengatur gaya pemisah baris untuk dokumen yang dihasilkan. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Jika nilai tidak ditentukan, maka gambar akan ditulis ke direktori yang sama dengan file markdown itu sendiri. Ini bukan path, hanya nama! Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Mendapatkan dan mengatur izin untuk mengonversi subskrip dan superskrip. Nilai ini bernilai true secara default. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Mendapatkan dan mengatur izin penggunaan tag img untuk menyisipkan gambar di kiri dan kanan teks. Dalam kasus ini, di penampil markdown, teks akan melilit gambar. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Dapatkan atau atur area persegi panjang untuk mengekstrak konten ke markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Mendapatkan atau mengatur gaya penekanan untuk dokumen yang dihasilkan. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Mendapatkan dan mengatur properti yang menunjukkan apakah grafik vektor harus diekstrak. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Mendefinisikan tingkat heading yang diharapkan untuk digunakan dalam strategi pengenalan header FontSize. Jika nilai properti ini diatur, maka strategi pengenalan header {@link HeadingRecognitionStrategy#Heuristic} akan dipilih ketika strategi {@link HeadingRecognitionStrategy#Auto} diatur meskipun dokumen berisi bookmark. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Mendapatkan atau mengatur strategi pengenalan heading. |
| [setHeadingStyle](#setHeadingStyle-int-) | Mendapatkan atau mengatur gaya heading untuk dokumen yang dihasilkan. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Mendapatkan atau mengatur gaya pemisah baris untuk dokumen yang dihasilkan. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Jika nilai tidak ditentukan, maka gambar akan ditulis ke direktori yang sama dengan file markdown itu sendiri. Ini bukan path, hanya nama! Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Mendapatkan dan mengatur izin untuk mengonversi subskrip dan superskrip. Nilai ini bernilai true secara default. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Mendapatkan dan mengatur izin penggunaan tag img untuk menyisipkan gambar di kiri dan kanan teks. Dalam kasus ini, di penampil markdown, teks akan melilit gambar. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Membuat opsi instance untuk menyimpan dokumen dalam format markdown.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Dapatkan atau atur area persegi panjang untuk mengekstrak konten ke markdown.

**Returns:**
Instansi Rectangle

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Mendapatkan atau mengatur gaya penekanan untuk dokumen yang dihasilkan.

**Returns:**
Elemen EmphasisStyle

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Mendapatkan dan mengatur properti yang menunjukkan apakah grafik vektor harus diekstrak.

**Returns:**
nilai boolean

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Mendefinisikan tingkat heading yang diharapkan untuk digunakan dalam strategi pengenalan header FontSize. Jika nilai properti ini diatur, maka strategi pengenalan header {@link HeadingRecognitionStrategy#Heuristic} akan dipilih ketika strategi {@link HeadingRecognitionStrategy#Auto} diatur meskipun dokumen berisi bookmark.

**Returns:**
Instansi HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Mendapatkan atau mengatur strategi pengenalan heading.

**Returns:**
Elemen HeadingRecognitionStrategy

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Mendapatkan atau mengatur gaya heading untuk dokumen yang dihasilkan.

**Returns:**
Elemen HeadingStyle

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Mendapatkan atau mengatur gaya pemisah baris untuk dokumen yang dihasilkan.

**Returns:**
Elemen LineBreakStyle

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Jika nilai tidak ditentukan, maka gambar akan ditulis ke direktori yang sama dengan file markdown itu sendiri. Ini bukan path, hanya nama! Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan.

**Returns:**
nilai String

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan.

**Returns:**
nilai String

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Mendapatkan dan mengatur izin untuk mengonversi subskrip dan superskrip. Nilai ini bernilai true secara default.

**Returns:**
nilai boolean

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Mendapatkan dan mengatur izin penggunaan tag img untuk menyisipkan gambar di kiri dan kanan teks. Dalam kasus ini, di penampil markdown, teks akan melilit gambar.

**Returns:**
nilai boolean

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Dapatkan atau atur area persegi panjang untuk mengekstrak konten ke markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Mendapatkan atau mengatur gaya penekanan untuk dokumen yang dihasilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen EmphasisStyle |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Mendapatkan dan mengatur properti yang menunjukkan apakah grafik vektor harus diekstrak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Mendefinisikan tingkat heading yang diharapkan untuk digunakan dalam strategi pengenalan header FontSize. Jika nilai properti ini diatur, maka strategi pengenalan header {@link HeadingRecognitionStrategy#Heuristic} akan dipilih ketika strategi {@link HeadingRecognitionStrategy#Auto} diatur meskipun dokumen berisi bookmark.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Mendapatkan atau mengatur strategi pengenalan heading.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen HeadingRecognitionStrategy |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Mendapatkan atau mengatur gaya heading untuk dokumen yang dihasilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen HeadingStyle |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Mendapatkan atau mengatur gaya pemisah baris untuk dokumen yang dihasilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen LineBreakStyle |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Jika nilai tidak ditentukan, maka gambar akan ditulis ke direktori yang sama dengan file markdown itu sendiri. Ini bukan path, hanya nama! Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Mendapatkan dan mengatur nama direktori untuk menyimpan sumber daya dokumen seperti gambar. Direktori ini akan secara otomatis dibuat di dalam direktori dengan file markdown yang disimpan.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Mendapatkan dan mengatur izin untuk mengonversi subskrip dan superskrip. Nilai ini bernilai true secara default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Mendapatkan dan mengatur izin penggunaan tag img untuk menyisipkan gambar di kiri dan kanan teks. Dalam kasus ini, di penampil markdown, teks akan melilit gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
