---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat bookmark dengan aksi yang ditentukan
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## Metode PdfContentEditor.CreateBookmarksAction

Membuat bookmark dengan aksi yang ditentukan.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| title | String | Judul bookmark. |
| color | Color | Warna judul bookmark. |
| boldFlag | Boolean | Flag atribusi tebal. |
| italicFlag | Boolean | Flag atribusi miring. |
| file | String | File atau aplikasi lain yang diperlukan ketika tipe aksi adalah "GoToR" atau "Launch". |
| actionType | String | Tipe aksi. Nilai dapat berupa: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | Tujuan lokal atau tujuan jarak jauh atau URL. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)