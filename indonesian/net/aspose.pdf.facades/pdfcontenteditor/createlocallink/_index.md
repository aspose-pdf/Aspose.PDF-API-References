---
title: PdfContentEditor.CreateLocalLink
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat tautan lokal dalam dokumen PDF
type: docs
weight: 190
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

Membuat tautan lokal dalam dokumen PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| desPage | Int32 | Halaman tujuan. |
| originalPage | Int32 | Nomor halaman asli di mana persegi panjang yang terikat dengan tautan lokal akan dibuat. |
| clr | Color | Warna persegi panjang untuk klik aktif. |
| actionName | Enum[] | Array tindakan (anggota enum PredefinedAction) yang sesuai dengan pelaksanaan item menu di penampil Acrobat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

Membuat tautan lokal dalam dokumen PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| desPage | Int32 | Halaman tujuan. |
| originalPage | Int32 | Nomor halaman asli di mana persegi panjang yang terikat dengan tautan lokal akan dibuat. |
| clr | Color | Warna persegi panjang untuk klik aktif. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

Membuat tautan lokal dalam dokumen PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| desPage | Int32 | Halaman tujuan. |
| originalPage | Int32 | Nomor halaman asli di mana persegi panjang yang terikat dengan tautan lokal akan dibuat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)