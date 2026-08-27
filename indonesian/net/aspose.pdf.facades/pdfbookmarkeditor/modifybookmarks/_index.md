---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfBookmarkEditor. Mengubah judul bookmark sesuai dengan judul bookmark yang ditentukan"
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

Mengubah judul bookmark sesuai dengan judul bookmark yang ditentukan.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sTitle | String | Judul bookmark sumber. |
| dTitle | String | Judul bookmark yang dimodifikasi. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


