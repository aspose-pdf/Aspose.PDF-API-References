---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase ukuran halaman awal."
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase ukuran halaman awal.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | Stream | Aliran yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri dalam persentase ukuran halaman awal. |
| rightMargin | Double | Margin kanan dalam persentase ukuran halaman awal. |
| topMargin | Double | Margin atas dalam persentase ukuran halaman awal. |
| bottomMargin | Double | Margin bawah dalam persentase ukuran halaman awal. |

### Nilai Kembalian

true jika aksi berhasil dilakukan.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //proses halaman 1, 2, 3
    new int[] { 1, 2, 3}, 
    //margin kiri adalah 15% dari lebar halaman
    15, 
    //margin kanan adalah 10% dari lebar halaman
    10, 
    //margin atas adalah 20% dari lebar halaman
    20, 
    //margin bawah adalah 5% dari lebar halaman
    5);
    dest.Close();
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase ukuran halaman awal.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | String | Jalur ke dokumen sumber. |
| destination | String | Jalur tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri dalam persentase ukuran halaman awal. |
| rightMargin | Double | Margin kanan dalam persentase ukuran halaman awal. |
| topMargin | Double | Margin atas dalam persentase ukuran halaman awal. |
| bottomMargin | Double | Margin bawah dalam persentase ukuran halaman awal. |

### Nilai Kembalian

true jika perubahan ukuran berhasil

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //proses halaman 1, 2, 3
    new int[] { 1, 2, 3}, 
    //margin kiri adalah 15% dari lebar halaman
    15, 
    //margin kanan adalah 10% dari lebar halaman
    10, 
    //margin atas adalah 20% dari lebar halaman
    20, 
    //margin bawah adalah 5% dari lebar halaman
    5);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


