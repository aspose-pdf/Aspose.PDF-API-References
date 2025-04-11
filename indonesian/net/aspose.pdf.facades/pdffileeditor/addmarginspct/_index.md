---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | Stream | Stream yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri dalam persentase dari ukuran halaman awal. |
| rightMargin | Double | Margin kanan dalam persentase dari ukuran halaman awal. |
| topMargin | Double | Margin atas dalam persentase dari ukuran halaman awal. |
| bottomMargin | Double | Margin bawah dalam persentase dari ukuran halaman awal. |

### Return Value

true jika tindakan berhasil dilakukan.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | String | Jalur ke dokumen sumber. |
| destination | String | Jalur tempat dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri dalam persentase dari ukuran halaman awal. |
| rightMargin | Double | Margin kanan dalam persentase dari ukuran halaman awal. |
| topMargin | Double | Margin atas dalam persentase dari ukuran halaman awal. |
| bottomMargin | Double | Margin bawah dalam persentase dari ukuran halaman awal. |

### Return Value

true jika pengubahan ukuran berhasil

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)