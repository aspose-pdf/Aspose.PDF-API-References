---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileEditor. Mengubah ukuran konten halaman dokumen
type: docs
weight: 450
url: /id/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman. Hasil disimpan ke dalam objek HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | String | Jalur ke file sumber. |
| pages | Int32[] | Array halaman yang akan diubah ukurannya. |
| parameters | ContentsResizeParameters | Parameter pengubahan ukuran. |
| response | HttpResponse | Objek HttpResponse di mana hasil disimpan. |

### Return Value

true jika operasi berhasil; jika tidak, false.

## Remarks

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman. Hasil disimpan ke dalam objek HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | Stream | Stream dari file sumber. |
| pages | Int32[] | Array halaman yang akan diubah ukurannya. |
| parameters | ContentsResizeParameters | Parameter pengubahan ukuran. |
| response | HttpResponse | Objek HttpResponse di mana hasil disimpan. |

### Return Value

true jika operasi berhasil; jika tidak, false.

## Remarks

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Mengubah ukuran konten halaman dokumen.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
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

## Remarks

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

## Examples

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

true jika operasi berhasil; jika tidak, false.

## Remarks

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

## Remarks

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

## Examples

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### See Also

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)