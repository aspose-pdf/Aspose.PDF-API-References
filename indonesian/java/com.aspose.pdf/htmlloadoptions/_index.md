---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi untuk memuat/mengimpor file HTML ke dalam dokumen PDF."
type: docs
weight: 1960
url: /id/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Mewakili opsi untuk memuat/mengimpor file HTML ke dalam dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Membuat opsi pemuatan untuk mengonversi html menjadi dokumen pdf dengan jalur dasar kosong. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Membuat opsi pemuatan untuk mengonversi html menjadi dokumen pdf dengan jalur dasar kosong. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBasePath](#getBasePath--) | Jalur dasar/url untuk file html. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | Kadang-kadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode khusus yang akan mengambil sumber daya yang diminta dari suatu tempat. Misalnya, selama penggunaan Aspose.PDF di cloud akses langsung ke file yang direferensikan tidak memungkinkan: dalam kasus seperti itu kode pelanggan yang ditempatkan ke metode khusus harus digunakan, dan delegasi yang merujuk ke metode tersebut harus ditetapkan ke atribut ini. |
| [getHtmlMediaType](#getHtmlMediaType--) | Mendapatkan atau mengatur tipe media yang mungkin digunakan selama rendering. |
| [getInputEncoding](#getInputEncoding--) | Mendapatkan atribut yang menentukan pengkodean yang digunakan untuk dokumen ini pada saat parsing. Jika atribut ini null, pengkodean akan ditentukan dari atribut set karakter dokumen. |
| [getPageInfo](#getPageInfo--) | Mendapatkan info halaman dokumen |
| [getPageLayoutOption](#getPageLayoutOption--) | Mendapatkan atau mengatur opsi tata letak. |
| [isEmbedFonts](#isEmbedFonts--) | Mendapatkan atau mengatur penyematan font ke dokumen hasil |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Mendapatkan atau mengatur flag yang menentukan bahwa aturan @page yang didefinisikan dalam css akan menimpa nilai yang didefinisikan dalam PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Mendapatkan atau mengatur rendering seluruh dokumen menjadi satu halaman |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Kadang-kadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode khusus yang akan mengambil sumber daya yang diminta dari suatu tempat. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Mendapatkan atau mengatur penyematan font ke dokumen hasil |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Mendapatkan atau mengatur tipe media yang mungkin digunakan selama rendering. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Mengatur atribut yang menentukan pengkodean yang digunakan untuk dokumen ini pada saat parsing. Jika atribut ini null, pengkodean akan ditentukan dari atribut set karakter dokumen. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Mengatur info halaman dokumen |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Mendapatkan atau mengatur opsi tata letak. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Mendapatkan atau mengatur flag yang menentukan bahwa aturan @page yang didefinisikan dalam css akan menimpa nilai yang didefinisikan dalam PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Mendapatkan atau mengatur rendering seluruh dokumen menjadi satu halaman |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Membuat opsi pemuatan untuk mengonversi html menjadi dokumen pdf dengan jalur dasar kosong.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Membuat opsi pemuatan untuk mengonversi html menjadi dokumen pdf dengan jalur dasar kosong.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Jalur dasar/url untuk file html.

**Returns:**
nilai String

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

Kadang-kadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode khusus yang akan mengambil sumber daya yang diminta dari suatu tempat. Misalnya, selama penggunaan Aspose.PDF di cloud akses langsung ke file yang direferensikan tidak memungkinkan: dalam kasus seperti itu kode pelanggan yang ditempatkan ke metode khusus harus digunakan, dan delegasi yang merujuk ke metode tersebut harus ditetapkan ke atribut ini.

**Returns:**
Instansi ResourceLoadingStrategy

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Mendapatkan atau mengatur tipe media yang mungkin digunakan selama rendering.

**Returns:**
Elemen HtmlMediaType

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Mendapatkan atribut yang menentukan pengkodean yang digunakan untuk dokumen ini pada saat parsing. Jika atribut ini null, pengkodean akan ditentukan dari atribut set karakter dokumen.

**Returns:**
nilai String

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Mendapatkan info halaman dokumen

**Returns:**
info halaman

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Mendapatkan atau mengatur opsi tata letak.

**Returns:**
Elemen HtmlPageLayoutOption @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Mendapatkan atau mengatur penyematan font ke dokumen hasil

**Returns:**
nilai boolean

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Mendapatkan atau mengatur flag yang menentukan bahwa aturan @page yang didefinisikan dalam css akan menimpa nilai yang didefinisikan dalam PageInfo.

**Returns:**
nilai boolean

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Mendapatkan atau mengatur rendering seluruh dokumen menjadi satu halaman

**Returns:**
nilai boolean

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
Kadang-kadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode khusus yang akan mengambil sumber daya yang diminta dari suatu tempat.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Mendapatkan atau mengatur penyematan font ke dokumen hasil

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Mendapatkan atau mengatur tipe media yang mungkin digunakan selama rendering.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Mengatur atribut yang menentukan pengkodean yang digunakan untuk dokumen ini pada saat parsing. Jika atribut ini null, pengkodean akan ditentukan dari atribut set karakter dokumen.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Mengatur info halaman dokumen

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Mendapatkan atau mengatur opsi tata letak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen HtmlPageLayoutOption @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Mendapatkan atau mengatur flag yang menentukan bahwa aturan @page yang didefinisikan dalam css akan menimpa nilai yang didefinisikan dalam PageInfo.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Mendapatkan atau mengatur rendering seluruh dokumen menjadi satu halaman

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
