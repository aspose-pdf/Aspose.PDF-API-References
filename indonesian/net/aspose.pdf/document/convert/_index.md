---
title: "Document.Convert"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Document. Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan"
type: docs
weight: 600
url: /id/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Mengonversi document dan menyimpan kesalahan ke dalam file yang ditentukan.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputLogFileName | String | Jalur ke file tempat komentar akan disimpan. |
| format | PdfFormat | Format pdf. |
| aksi | ConvertErrorAction | Aksi untuk objek yang tidak dapat dikonversi |
| transparencyAction | ConvertTransparencyAction | Aksi untuk objek gambar yang dimask. |

### Nilai Kembalian

Hasil operasi

### Lihat Juga

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Mengonversi document dan menyimpan kesalahan ke dalam file yang ditentukan.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputLogStream | Stream | Stream tempat komentar akan disimpan. |
| format | PdfFormat | Format pdf. |
| aksi | ConvertErrorAction | Aksi untuk objek yang tidak dapat dikonversi |
| transparencyAction | ConvertTransparencyAction | Aksi untuk objek gambar yang dimask. |

### Nilai Kembalian

Hasil operasi

### Lihat Juga

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Mengonversi document dan menyimpan kesalahan ke dalam file yang ditentukan.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputLogFileName | String | Jalur ke file tempat komentar akan disimpan. |
| format | PdfFormat | Format pdf. |
| aksi | ConvertErrorAction | Aksi untuk objek yang tidak dapat dikonversi |

### Nilai Kembalian

Hasil operasi

### Lihat Juga

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Mengonversi document menggunakan opsi konversi yang ditentukan.

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | PdfFormatConversionOptions | sekumpulan opsi untuk mengonversi dokumen PDF |

### Nilai Kembalian

Hasil operasi

### Lihat Juga

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Mengenali gambar di dalam document dan menambahkan string hocr di atasnya.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Aksi untuk gambar yang akan diproses oleh pengenalan hocr. |
| flattenImages | Boolean | Teks dalam gambar pdf dapat digambar menggunakan mekanisme masker, dalam hal ini gambar harus diratakan. |

### Nilai Kembalian

Hasil operasi. Jika tidak ada gambar dalam dokumen mengembalikan !:false.

### Lihat Juga

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Mengenali gambar di dalam document dan menambahkan string hocr di atasnya.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | CallBackGetHocr | Aksi untuk gambar yang akan diproses oleh pengenalan hocr. |
| flattenImages | Boolean | Teks dalam gambar pdf dapat digambar menggunakan mekanisme masker, dalam hal ini gambar harus diratakan. |

### Nilai Kembalian

Hasil operasi. Jika tidak ada gambar dalam dokumen mengembalikan !:false.

### Lihat Juga

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Mengonversi document dan menyimpan kesalahan ke dalam stream yang ditentukan.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputLogStream | Stream | Stream tempat komentar akan disimpan. |
| format | PdfFormat | Format Pdf. |
| aksi | ConvertErrorAction | Aksi untuk objek yang tidak dapat dikonversi |

### Nilai Kembalian

Hasil operasi

### Lihat Juga

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Mengonversi document dengan menerapkan Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fixup | Fixup | Tipe Fixup. |
| outputLog | Stream | Log proses. |
| onlyValidation | Boolean | Hanya validasi dokumen. |
| parameter | Object[] | Properti untuk Fixup yang tidak dapat diatur. |

### Nilai Kembalian

Hasil operasi.

### Lihat Juga

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Mengonversi document dengan menerapkan Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fixup | Fixup | Tipe Fixup. |
| outputLog | String | Log proses. |
| onlyValidation | Boolean | Hanya validasi dokumen. |
| parameter | Object[] | Properti untuk Fixup yang tidak dapat diatur. |

### Nilai Kembalian

Hasil operasi.

### Lihat Juga

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Mengonversi file sumber dalam format sumber menjadi file tujuan dalam format tujuan.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama file sumber. |
| loadOptions | LoadOptions | Format file sumber. |
| dstFileName | String | Nama file tujuan. |
| saveOptions | SaveOptions | Format file tujuan. |

### Lihat Juga

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Mengonversi stream dalam format sumber menjadi file tujuan dalam format tujuan.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcStream | Stream | Stream sumber. |
| loadOptions | LoadOptions | Format stream sumber. |
| dstFileName | String | Nama file tujuan. |
| saveOptions | SaveOptions | Format file tujuan. |

### Lihat Juga

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Mengonversi file sumber dalam format sumber menjadi stream dalam format tujuan.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama file sumber. |
| loadOptions | LoadOptions | Format file sumber. |
| dstStream | Stream | Aliran tujuan. |
| saveOptions | SaveOptions | Format stream tujuan. |

### Lihat Juga

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Mengonversi stream dalam format sumber menjadi stream dalam format tujuan.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcStream | Stream | Stream sumber. |
| loadOptions | LoadOptions | Format stream sumber. |
| dstStream | Stream | Aliran tujuan. |
| saveOptions | SaveOptions | Format file tujuan. |

### Lihat Juga

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


