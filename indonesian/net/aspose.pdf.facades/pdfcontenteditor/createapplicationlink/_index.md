---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat tautan untuk meluncurkan aplikasi dalam dokumen PDF
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Membuat tautan untuk meluncurkan aplikasi dalam dokumen PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| application | String | Jalur aplikasi yang akan diluncurkan. |
| page | Int32 | Nomor halaman asli di mana persegi panjang yang terikat dengan tautan akan dibuat. |
| clr | Color | Warna persegi panjang untuk klik aktif. |
| actionName | Enum[] | Array tindakan (anggota enum PredefinedAction) yang sesuai dengan menjalankan item menu di penampil Acrobat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Membuat tautan untuk meluncurkan aplikasi dalam dokumen PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| application | String | Jalur aplikasi yang akan diluncurkan. |
| page | Int32 | Nomor halaman asli di mana persegi panjang yang terikat dengan tautan akan dibuat. |
| clr | Color | Warna persegi panjang untuk klik aktif. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Membuat tautan untuk meluncurkan aplikasi dalam dokumen PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| application | String | Jalur aplikasi yang akan diluncurkan. |
| page | Int32 | Nomor halaman asli di mana persegi panjang yang terikat dengan tautan akan dibuat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)