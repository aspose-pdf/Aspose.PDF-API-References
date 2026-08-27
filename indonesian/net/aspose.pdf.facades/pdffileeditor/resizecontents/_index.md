---
title: "PdfFileEditor.ResizeContents"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Mengubah ukuran konten halaman dokumen"
type: docs
weight: 320
url: /id/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Mengubah ukuran konten halaman dokumen.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | Stream | Stream dengan dokumen sumber. |
| destination | Stream | Stream dengan dokumen tujuan. |
| halaman | Int32[] | Array indeks halaman. |
| parameter | ContentsResizeParameters | Parameter pengubahan ukuran. |

### Nilai Kembalian

Mengembalikan true jika berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margin kiri = 10% dari lebar halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //lebar konten baru dihitung secara otomatis sebagai lebar - margin kiri - margin kanan (100% - 10% - 10% = 80%)
    null,
    //margin kanan adalah 10% dari halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margin atas = 10% dari tinggi
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //tinggi konten baru dihitung secara otomatis (mirip dengan lebar)
    null,
    //margin bawah adalah 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Lihat Juga

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | Stream | Aliran yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru dari konten halaman dalam satuan ruang default. |
| newHeight | Double | Tinggi baru dari konten halaman dalam satuan ruang default. |

### Nilai Kembalian

True jika perubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//ubah ukuran semua halaman dokumen
null, 
//lebar konten baru = 200
200, 
//tinggi konten baru = 300
300);
// sisa area halaman akan kosong
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | String | Jalur ke dokumen sumber. |
| destination | String | Jalur tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru dari konten halaman dalam satuan ruang default. |
| newHeight | Double | Tinggi baru dari konten halaman dalam satuan ruang default. |

### Nilai Kembalian

true jika perubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//ubah ukuran semua halaman dokumen
null, 
//lebar konten baru = 200
200, 
//tinggi konten baru = 300
300);
// sisa area halaman akan kosong
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekeliling halaman.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | String | Jalur dokumen sumber. |
| destination | String | Jalur dokumen tujuan. |
| halaman | Int32[] | Array indeks halaman (indeks halaman dimulai dari 1). |
| parameter | ContentsResizeParameters | Parameter pengubahan ukuran halaman. |

### Nilai Kembalian

true jika perubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margin kiri = 10% dari lebar halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //lebar konten baru dihitung secara otomatis sebagai lebar - margin kiri - margin kanan (100% - 10% - 10% = 80%)
    null,
    //margin kanan adalah 10% dari halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margin atas = 10% dari tinggi
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //tinggi konten baru dihitung secara otomatis (mirip dengan lebar)
    null,
    //margin bawah adalah 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Lihat Juga

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Mengubah ukuran halaman dokumen. Margin kosong ditambahkan di sekitar halaman yang diperkecil.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | Document | Dokumen sumber. |
| halaman | Int32[] | Daftar indeks halaman. |
| parameter | ContentsResizeParameters | Parameter pengubahan ukuran. |

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margin kiri = 10% dari lebar halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //lebar konten baru dihitung secara otomatis sebagai lebar - margin kiri - margin kanan (100% - 10% - 10% = 80%)
    null,
    //margin kanan adalah 10% dari halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margin atas = 10% dari tinggi
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //tinggi konten baru dihitung secara otomatis (mirip dengan lebar)
    null,
    //margin bawah adalah 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Mengubah ukuran halaman dokumen. Margin kosong ditambahkan di sekitar halaman yang diperkecil.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber | Document | Dokumen sumber. |
| parameter | ContentsResizeParameters | Parameter pengubahan ukuran. |

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margin kiri = 10% dari lebar halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //lebar konten baru dihitung secara otomatis sebagai lebar - margin kiri - margin kanan (100% - 10% - 10% = 80%)
    null,
    //margin kanan adalah 10% dari halaman
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margin atas = 10% dari tinggi
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //tinggi konten baru dihitung secara otomatis (mirip dengan lebar)
    null,
    //margin bawah adalah 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Lihat Juga

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


