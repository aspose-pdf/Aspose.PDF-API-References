---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Mengubah ukuran konten halaman dokumen. Mengurangi konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Mengubah ukuran konten halaman dokumen. Mengurangi konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | Stream | Stream yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru konten halaman dalam persentase. |
| newHeight | Double | Tinggi baru konten halaman dalam persentase. |

### Return Value

true jika berhasil diubah ukurannya.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Mengubah ukuran konten halaman dokumen. Mengurangi konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | String | Jalur ke dokumen sumber. |
| destination | String | Jalur tempat dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru konten halaman dalam persentase. |
| newHeight | Double | Tinggi baru konten halaman dalam persentase. |

### Return Value

true jika pengubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)