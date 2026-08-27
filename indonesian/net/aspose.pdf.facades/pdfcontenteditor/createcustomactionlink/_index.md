---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat tautan ke aksi khusus dalam dokumen PDF"
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

Membuat tautan ke aksi khusus dalam dokumen PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| originalPage | Int32 | Nomor halaman asli tempat persegi panjang yang terikat dengan tautan akan dibuat. |
| color | Color | Warna persegi panjang untuk klik aktif. |
| actionName | Enum[] | Array tindakan (anggota enum PredefinedAction) yang sesuai dengan mengeksekusi item menu di penampil Acrobat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


