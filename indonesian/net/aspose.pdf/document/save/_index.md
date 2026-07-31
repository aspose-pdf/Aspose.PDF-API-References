---
title: "Document.Save"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Document. Menyimpan dokumen ke stream dengan opsi penyimpanan"
type: docs
weight: 850
url: /id/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

Menyimpan dokumen ke stream dengan opsi penyimpanan.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat dokumen akan disimpan. |
| options | SaveOptions | Opsi penyimpanan. |

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

## Save(Stream) {#save_2}

Menyimpan dokumen ke dalam stream.

```csharp
public void Save(Stream output)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | Stream | Stream tempat dokumen akan disimpan. |

### Lihat Juga

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Menyimpan dokumen ke file yang ditentukan.

```csharp
public void Save(string outputFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |

### Lihat Juga

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

Simpan dokumen secara inkremental (misalnya menggunakan teknik pembaruan inkremental).

```csharp
public void Save()
```

## Catatan

Untuk menyimpan dokumen secara inkremental, kita harus membuka file dokumen untuk menulis. Oleh karena itu Document harus diinisialisasi dengan aliran yang dapat ditulis seperti pada potongan kode berikut: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // lakukan beberapa perubahan dan simpan dokumen secara inkremental doc.Save();

### Lihat Juga

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Menyimpan dokumen dengan opsi penyimpanan.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | SaveOptions | Opsi penyimpanan. |

### Lihat Juga

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Menyimpan dokumen dengan nama baru beserta format file.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| format | SaveFormat | Opsi format. |

### Lihat Juga

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Menyimpan dokumen dengan nama baru beserta format file.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat dokumen akan disimpan. |
| format | SaveFormat | Opsi format. |

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

## Save(string, SaveOptions) {#save_7}

Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | String | Jalur ke file tempat dokumen akan disimpan. |
| options | SaveOptions | Opsi penyimpanan. |

### Lihat Juga

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


