---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Memisahkan file Pdf dari halaman pertama ke lokasi yang ditentukan dan menyimpan bagian depan sebagai file baru
type: docs
weight: 460
url: /id/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Memisahkan file Pdf dari halaman pertama ke lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | File Pdf sumber. |
| location | Int32 | Titik pemisahan. |
| outputFile | String | File Pdf keluaran. |

### Nilai Kembali

True untuk sukses, atau false.

## Catatan

Metode TrySplitFromFirst mirip dengan metode SplitFromFirst, kecuali metode TrySplitFromFirst tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Memisahkan dari awal ke lokasi yang ditentukan, dan menyimpan bagian depan dalam Stream keluaran.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file Pdf sumber. |
| location | Int32 | Titik pemisahan. |
| outputStream | Stream | Stream file keluaran. |

### Nilai Kembali

True untuk sukses, atau false.

## Catatan

Stream TIDAK ditutup setelah operasi ini. Metode TrySplitFromFirst mirip dengan metode SplitFromFirst, kecuali metode TrySplitFromFirst tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Memisahkan dokumen dari halaman pertama ke lokasi dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Nama file sumber. |
| location | Int32 | Titik pemisahan. |
| response | HttpResponse | Objek HttpResponse. |

### Nilai Kembali

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TrySplitFromFirst mirip dengan metode SplitFromFirst, kecuali metode TrySplitFromFirst tidak melempar pengecualian jika operasi gagal.

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Memisahkan dokumen dari awal ke lokasi yang ditentukan dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dokumen sumber. |
| location | Int32 | Titik pemisahan. |
| response | HttpResponse | Objek HttpResponse di mana hasil akan disimpan. |

### Nilai Kembali

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TrySplitFromFirst mirip dengan metode SplitFromFirst, kecuali metode TrySplitFromFirst tidak melempar pengecualian jika operasi gagal.

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)