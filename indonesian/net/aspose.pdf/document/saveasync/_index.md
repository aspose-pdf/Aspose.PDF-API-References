---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode dokumen. Menyimpan dokumen ke dalam stream
type: docs
weight: 840
url: /id/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Menyimpan dokumen ke dalam stream.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | Stream | Stream tempat dokumen akan disimpan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Menyimpan dokumen ke dalam file yang ditentukan.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Menyimpan dokumen secara inkremental (misalnya, menggunakan teknik pembaruan inkremental).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

## Catatan

Untuk menyimpan dokumen secara inkremental, kita harus membuka file dokumen untuk menulis. Oleh karena itu, Dokumen harus diinisialisasi dengan stream yang dapat ditulis seperti dalam cuplikan kode berikut: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // lakukan beberapa perubahan dan simpan dokumen secara inkremental doc.Save();

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Menyimpan dokumen dengan opsi penyimpanan.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | SaveOptions | Opsi penyimpanan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

### Lihat Juga

* kelas [SaveOptions](../../saveoptions/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Menyimpan dokumen dengan nama baru bersama dengan format file.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| format | SaveFormat | Opsi format. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

### Lihat Juga

* enum [SaveFormat](../../saveformat/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Menyimpan dokumen dengan nama baru bersama dengan format file.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat dokumen akan disimpan. |
| format | SaveFormat | Opsi format. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | ArgumentException ketika [`HtmlSaveOptions`](../../htmlsaveoptions/) diteruskan ke metode. Menyimpan dokumen ke stream html tidak didukung. Silakan gunakan metode simpan ke file. |

### Lihat Juga

* enum [SaveFormat](../../saveformat/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Menyimpan dokumen dengan nama baru dengan mengatur opsi penyimpanannya.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| options | SaveOptions | Opsi penyimpanan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

### Lihat Juga

* kelas [SaveOptions](../../saveoptions/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Menyimpan dokumen ke stream dengan opsi penyimpanan.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat dokumen akan disimpan. |
| options | SaveOptions | Opsi penyimpanan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Return Value

Tugas asinkron.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | ArgumentException ketika [`HtmlSaveOptions`](../../htmlsaveoptions/) diteruskan ke metode. Menyimpan dokumen ke stream html tidak didukung. Silakan gunakan metode simpan ke file. |

### Lihat Juga

* kelas [SaveOptions](../../saveoptions/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)