---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default
type: docs
weight: 220
url: /id/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | Stream | Stream yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri. |
| rightMargin | Double | Margin kanan. |
| topMargin | Double | Margin atas. |
| bottomMargin | Double | Margin bawah. |

### Return Value

true jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | String | Jalur ke dokumen sumber. |
| destination | String | Jalur tempat dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri. |
| rightMargin | Double | Margin kanan. |
| topMargin | Double | Margin atas. |
| bottomMargin | Double | Margin bawah. |

### Return Value

true jika pengubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)