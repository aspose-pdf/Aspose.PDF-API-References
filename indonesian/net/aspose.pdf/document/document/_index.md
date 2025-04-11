---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Konstruktor Dokumen. Inisialisasi instance Dokumen baru dari aliran input
type: docs
weight: 10
url: /id/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Inisialisasi instance Dokumen baru dari aliran *input*.

```csharp
public Document(Stream input)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | Stream | Aliran dengan dokumen pdf. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

Inisialisasi instance Dokumen baru dari aliran *input*.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | Stream | Aliran dengan dokumen pdf. |
| isManagedStream | Boolean | jika diatur ke `true` aliran dalam ditutup sebelum keluar; jika tidak, tidak. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

Inisialisasi instance Dokumen baru dari aliran *input*.

```csharp
public Document(Stream input, string password)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | Stream | Objek aliran input, pdf yang sesuai dilindungi kata sandi. |
| password | String | Kata sandi pengguna atau pemilik. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

Inisialisasi instance Dokumen baru dari aliran *input*.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | Stream | Aliran dengan dokumen pdf. |
| password | String | Kata sandi pengguna atau pemilik. |
| isManagedStream | Boolean | Jika diatur ke `true` aliran dalam ditutup sebelum keluar; jika tidak, tidak. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

Hanya inisialisasi Dokumen menggunakan *nama file*. Sama seperti `Document`.

```csharp
public Document(string filename)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | String | Nama file dokumen pdf. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

Hanya inisialisasi Dokumen menggunakan *nama file*. Sama seperti `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | String | Nama file dokumen pdf. |
| isManagedStream | Boolean | Jika diatur ke `true` aliran dalam ditutup sebelum keluar; jika tidak, tidak. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

Menginisialisasi instance baru dari kelas [`Document`](../) untuk bekerja dengan dokumen terenkripsi.

```csharp
public Document(string filename, string password)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | String | Nama file dokumen. |
| password | String | Kata sandi pengguna atau pemilik. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

Menginisialisasi instance baru dari kelas [`Document`](../) untuk bekerja dengan dokumen terenkripsi.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | String | Nama file dokumen. |
| password | String | Kata sandi pengguna atau pemilik. |
| isManagedStream | Boolean | jika diatur ke `true` aliran dalam ditutup sebelum keluar; jika tidak, tidak. |

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Menginisialisasi dokumen kosong.

```csharp
public Document()
```

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Menginisialisasi dokumen kosong berdasarkan versi.

```csharp
public Document(PdfVersion version)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| version | PdfVersion | Versi PDF. |

### Lihat Juga

* enum [PdfVersion](../../pdfversion/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

Membuka dokumen yang ada dari file dengan memberikan opsi konversi yang diperlukan untuk mendapatkan dokumen pdf.

```csharp
public Document(string filename, LoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | String | File input untuk dikonversi menjadi dokumen pdf. |
| options | LoadOptions | Mewakili properti untuk mengonversi *filename* menjadi dokumen pdf. |

### Lihat Juga

* kelas [LoadOptions](../../loadoptions/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Membuka dokumen yang ada dari aliran dengan memberikan konversi yang diperlukan untuk mendapatkan dokumen pdf.

```csharp
public Document(Stream input, LoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | Stream | Aliran input untuk dikonversi menjadi dokumen pdf. |
| options | LoadOptions | Mewakili properti untuk mengonversi *input* menjadi dokumen pdf. |

### Lihat Juga

* kelas [LoadOptions](../../loadoptions/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)