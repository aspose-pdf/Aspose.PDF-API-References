---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Mengekstrak halaman dari file input dan menyimpannya sebagai file Pdf baru
type: docs
weight: 410
url: /id/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Mengekstrak halaman dari file input, menyimpannya sebagai file Pdf baru.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file Pdf input. |
| startPage | Int32 | Nomor halaman awal. |
| endPage | Int32 | Nomor halaman akhir. |
| outputFile | String | Jalur file Pdf output. |

### Nilai Kembali

True untuk sukses, atau false.

## Catatan

Metode TryExtract mirip dengan metode Extract, kecuali metode TryExtract tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file PDF baru.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputFile | String | Jalur file output. |

### Nilai Kembali

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryExtract mirip dengan metode Extract, kecuali metode TryExtract tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file Pdf baru.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream file input. |
| pageNumber | Int32[] | Indeks halaman dari file input. |
| outputStream | Stream | Stream file output. |

### Nilai Kembali

True untuk sukses, atau false.

## Catatan

Metode TryExtract mirip dengan metode Extract, kecuali metode TryExtract tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Stream dokumen sumber. |
| pageNumber | Int32[] | Array nomor halaman yang akan diekstrak. |
| response | HttpResponse | Objek HttpResponse di mana hasil akan disimpan. |

### Nilai Kembali

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryExtract mirip dengan metode Extract, kecuali metode TryExtract tidak melempar pengecualian jika operasi gagal.

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasilnya ke dalam objek HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file sumber. |
| pageNumber | Int32[] | Array nomor halaman yang akan diekstrak. |
| response | HttpResponse | Objek HttpResponse di mana hasil akan disimpan. |

### Nilai Kembali

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryExtract mirip dengan metode Extract, kecuali metode TryExtract tidak melempar pengecualian jika operasi gagal.

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)