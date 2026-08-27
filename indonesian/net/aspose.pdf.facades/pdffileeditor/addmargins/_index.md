---
title: "PdfFileEditor.AddMargins"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default."
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
| sumber | Stream | Aliran yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri. |
| rightMargin | Double | Margin kanan. |
| topMargin | Double | Margin atas. |
| bottomMargin | Double | Margin bawah. |

### Nilai Kembalian

true jika operasi berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //proses halaman 1, 2, 3
    new int[] { 1, 2, 3}, 
    //margin kiri adalah 10 unit
    10, 
    //margin kanan adalah 5 unit
    5, 
    //margin atas adalah 5 unit
    5, 
    //margin bawah adalah 5 unit
    5);
    dest.Close();
```

### Lihat Juga

* class [PdfFileEditor](../)
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
| sumber | String | Jalur ke dokumen sumber. |
| destination | String | Jalur tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| leftMargin | Double | Margin kiri. |
| rightMargin | Double | Margin kanan. |
| topMargin | Double | Margin atas. |
| bottomMargin | Double | Margin bawah. |

### Nilai Kembalian

true jika perubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //proses halaman 1, 2, 3
    new int[] { 1, 2, 3}, 
    //margin kiri adalah 10 unit
    10, 
    //margin kanan adalah 5 unit
    5, 
    //margin atas adalah 5 unit
    5, 
    //margin bawah adalah 5 unit
    5);
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


