---
title: "PdfFileEditor.TryResizeContents"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileEditor. Mengubah ukuran konten halaman dokumen"
type: docs
weight: 450
url: /id/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Mengubah ukuran konten halaman dokumen.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
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

## Catatan

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Lihat Juga

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
| sumber | Stream | Aliran yang berisi dokumen sumber. |
| destination | Stream | Stream tempat dokumen hasil akan disimpan. |
| halaman | Int32[] | Array indeks halaman. Jika null maka semua halaman dokumen akan diproses. |
| newWidth | Double | Lebar baru dari konten halaman dalam satuan ruang default. |
| newHeight | Double | Tinggi baru dari konten halaman dalam satuan ruang default. |

### Nilai Kembalian

true jika operasi selesai dengan sukses; jika tidak, false.

## Catatan

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

## Contoh

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekeliling halaman.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

## Catatan

Metode TryResizeContents mirip dengan metode ResizeContents, kecuali metode TryResizeContents tidak melempar pengecualian jika operasi gagal.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Lihat Juga

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


