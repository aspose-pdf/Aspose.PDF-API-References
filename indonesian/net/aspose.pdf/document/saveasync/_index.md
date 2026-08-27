---
title: "Document.SaveAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Document. Menyimpan dokumen ke stream dengan opsi penyimpanan"
type: docs
weight: 860
url: /id/net/aspose.pdf/document/saveasync/
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

### Nilai Kembalian

Tugas asinkron.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | ArgumentException ketika [`HtmlSaveOptions`](../../htmlsaveoptions/) diteruskan ke sebuah metode. Menyimpan dokumen ke stream html tidak didukung. Silakan gunakan metode simpan ke file. |

### Lihat Juga

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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

### Nilai Kembalian

Tugas asinkron.

### Lihat Juga

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Menyimpan dokumen ke file yang ditentukan.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Nilai Kembalian

Tugas asinkron.

### Lihat Juga

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Simpan dokumen secara inkremental (misalnya menggunakan teknik pembaruan inkremental).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cancellationToken | CancellationToken | Token pembatalan. |

### Nilai Kembalian

Tugas asinkron.

## Catatan

Untuk menyimpan dokumen secara inkremental, kita harus membuka file dokumen untuk menulis. Oleh karena itu Document harus diinisialisasi dengan aliran yang dapat ditulis seperti pada potongan kode berikut: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // lakukan beberapa perubahan dan simpan dokumen secara inkremental doc.Save();

### Lihat Juga

* class [Document](../)
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

### Nilai Kembalian

Tugas asinkron.

### Lihat Juga

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Menyimpan dokumen dengan nama baru beserta format file.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| format | SaveFormat | Opsi format. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Nilai Kembalian

Tugas asinkron.

### Lihat Juga

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Menyimpan dokumen dengan nama baru beserta format file.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat dokumen akan disimpan. |
| format | SaveFormat | Opsi format. |
| cancellationToken | CancellationToken | Token pembatalan |

### Nilai Kembalian

Tugas asinkron.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | ArgumentException ketika [`HtmlSaveOptions`](../../htmlsaveoptions/) diteruskan ke sebuah metode. Menyimpan dokumen ke stream html tidak didukung. Silakan gunakan metode simpan ke file. |

### Lihat Juga

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| options | SaveOptions | Opsi penyimpanan. |
| cancellationToken | CancellationToken | Token pembatalan. |

### Nilai Kembalian

Tugas asinkron.

### Lihat Juga

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


