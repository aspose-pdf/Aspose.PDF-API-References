---
title: "PdfContentEditor.CreateBookmarksAction"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat bookmark dengan aksi yang ditentukan"
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

Membuat bookmark dengan aksi yang ditentukan.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| title | String | Judul bookmark. |
| color | Color | Warna judul bookmark. |
| boldFlag | Boolean | Bendera atribut tebal. |
| italicFlag | Boolean | Bendera atribut miring. |
| file | String | File atau aplikasi lain yang diperlukan ketika tipe aksi adalah "GoToR" atau "Launch". |
| actionType | String | Tipe aksi. Nilainya dapat berupa: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | Tujuan lokal atau tujuan remote atau URL. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


