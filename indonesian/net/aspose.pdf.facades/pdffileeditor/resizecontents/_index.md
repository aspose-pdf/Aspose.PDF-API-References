---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Mengubah ukuran konten halaman dokumen
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
| source | Stream | Stream dengan dokumen sumber. |
| destination | Stream | Stream dengan dokumen tujuan. |
| pages | Int32[] | Array indeks halaman. |
| parameters | ContentsResizeParameters | Parameter pengubahan ukuran. |

### Return Value

Mengembalikan true jika berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Lihat Juga

* kelas [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Mengubah ukuran konten halaman dokumen. Mengurangi konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | Stream | Stream yang berisi dokumen sumber. |
| destination | Stream | Stream di mana dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null, maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru konten halaman dalam satuan ruang default. |
| newHeight | Double | Tinggi baru konten halaman dalam satuan ruang default. |

### Return Value

True jika pengubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Mengubah ukuran konten halaman dokumen. Mengurangi konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | String | Jalur ke dokumen sumber. |
| destination | String | Jalur di mana dokumen hasil akan disimpan. |
| pages | Int32[] | Array indeks halaman. Jika null, maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru konten halaman dalam satuan ruang default. |
| newHeight | Double | Tinggi baru konten halaman dalam satuan ruang default. |

### Return Value

true jika pengubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | String | Jalur dokumen sumber. |
| destination | String | Jalur dokumen tujuan. |
| pages | Int32[] | Array indeks halaman (indeks halaman dimulai dari 1). |
| parameters | ContentsResizeParameters | Parameter pengubahan ukuran halaman. |

### Return Value

true jika pengubahan ukuran berhasil.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Lihat Juga

* kelas [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* kelas [PdfFileEditor](../)
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
| source | Document | Dokumen sumber. |
| pages | Int32[] | Daftar indeks halaman. |
| parameters | ContentsResizeParameters | Parameter pengubahan ukuran. |

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Lihat Juga

* kelas [Document](../../../aspose.pdf/document/)
* kelas [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* kelas [PdfFileEditor](../)
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
| source | Document | Dokumen sumber. |
| parameters | ContentsResizeParameters | Parameter pengubahan ukuran. |

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Lihat Juga

* kelas [Document](../../../aspose.pdf/document/)
* kelas [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)