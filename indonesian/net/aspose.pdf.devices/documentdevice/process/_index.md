---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Metode DocumentDevice. Setiap perangkat mewakili beberapa operasi pada dokumen, misalnya kita dapat mengonversi dokumen pdf ke format lain
type: docs
weight: 10
url: /id/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Setiap perangkat mewakili beberapa operasi pada dokumen, misalnya kita dapat mengonversi dokumen pdf ke format lain.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Document | Dokumen yang akan diproses. |
| fromPage | Int32 | Menentukan halaman dari mana pemrosesan dimulai. |
| toPage | Int32 | Menentukan halaman terakhir yang akan diproses. |
| output | Stream | Menentukan stream di mana hasil pemrosesan disimpan. |

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Memproses seluruh dokumen dan menyimpan hasilnya ke dalam stream.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Document | Dokumen yang akan diproses. |
| output | Stream | Menentukan stream di mana hasil pemrosesan disimpan. |

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Memproses seluruh dokumen dan menyimpan hasilnya ke dalam file.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Document | Dokumen yang akan diproses. |
| outputFileName | String | Menentukan file di mana hasil pemrosesan disimpan. |

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Memproses halaman tertentu dari dokumen dan menyimpan hasilnya ke dalam file.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | Document | Dokumen yang akan diproses. |
| fromPage | Int32 | Halaman pertama untuk memulai pemrosesan. |
| toPage | Int32 | Halaman terakhir dari pemrosesan. |
| outputFileName | String | Menentukan file di mana hasil pemrosesan disimpan. |

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)