---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileEditor method. Mengubah ukuran konten halaman dokumen. Mengecilkan konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase."
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persen.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | Stream | Aliran yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru konten halaman dalam persentase. |
| newHeight | Double | Tinggi baru konten halaman dalam persentase. |

### Nilai Kembalian

true jika berhasil diubah ukurannya.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//ubah ukuran semua halaman dokumen
null, 
//lebar konten baru = 60% dari ukuran awal
60, 
//tinggi konten baru = 60% dari ukuran awal
60);
// Sisa area halaman akan kosong (margin halaman). Ukuran margin kiri dan kanan adalah (100% - 60%) / 2 = 20%
// Hal yang sama untuk margin atas dan bawah.
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persen.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | String | Jalur ke dokumen sumber. |
| destination | String | Jalur tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru konten halaman dalam persentase. |
| newHeight | Double | Tinggi baru konten halaman dalam persentase. |

### Nilai Kembalian

true jika perubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//ubah ukuran semua halaman dokumen
null, 
//lebar konten baru = 60% dari ukuran awal
60, 
//tinggi konten baru = 60% dari ukuran awal
60);
// Sisa area halaman akan kosong (margin halaman). Ukuran margin kiri dan kanan adalah (100% - 60%) / 2 = 20%
// Hal yang sama untuk margin atas dan bawah.
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


