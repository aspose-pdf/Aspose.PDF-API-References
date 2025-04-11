---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi lampiran file
type: docs
weight: 150
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Membuat anotasi lampiran file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| filePath | String | Jalur file yang akan dilampirkan. |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| name | String | Nama ikon yang akan digunakan untuk menampilkan anotasi. Nilai ini dapat berupa: "Graph", "PushPin", "Paperclip", "Tag". |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Membuat anotasi lampiran file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| filePath | String | Jalur file yang akan dilampirkan. |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| name | String | Nama ikon yang akan digunakan untuk menampilkan anotasi. Nilai ini dapat berupa: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opasitas ikon dari 0 hingga 1: 0 - sepenuhnya transparan, 1 - sepenuhnya tidak transparan. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Membuat anotasi lampiran file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| attachmentStream | Stream | Aliran file lampiran. |
| attachmentName | String | Nama lampiran. |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| name | String | Nama ikon yang akan digunakan untuk menampilkan anotasi. Nilai ini dapat berupa: "Graph", "PushPin", "Paperclip", "Tag". |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Membuat anotasi lampiran file.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| attachmentStream | Stream | Aliran file lampiran. |
| attachmentName | String | Nama lampiran. |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| name | String | Nama ikon yang akan digunakan untuk menampilkan anotasi. Nilai ini dapat berupa: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opasitas ikon dari 0 hingga 1: 0 - sepenuhnya transparan, 1 - sepenuhnya tidak transparan. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)