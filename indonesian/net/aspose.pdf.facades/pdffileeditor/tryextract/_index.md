---
title: "PdfFileEditor.TryExtract"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileEditor method. Mengekstrak halaman dari file masukan dan menyimpannya sebagai file Pdf baru."
type: docs
weight: 410
url: /id/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Mengekstrak halaman dari file input, menyimpan sebagai file Pdf baru.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Jalur file Pdf input. |
| startPage | Int32 | Nomor halaman mulai. |
| endPage | Int32 | Nomor halaman akhir. |
| outputFile | String | Jalur file Pdf keluaran. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Catatan

Metode TryExtract mirip dengan metode Extract, kecuali metode TryExtract tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFile | String | Path file input. |
| pageNumber | Int32[] | Indeks halaman di luar file input. |
| outputFile | String | Path file output. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryExtract mirip dengan metode Extract, kecuali metode TryExtract tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran file masukan. |
| pageNumber | Int32[] | Indeks halaman di luar file input. |
| outputStream | Stream | Aliran file output. |

### Nilai Kembalian

True untuk berhasil, atau false.

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

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


