---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metodu. Belirtilen yer imi başlığına göre yer imi başlığını değiştirir
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks metodu

Belirtilen yer imi başlığına göre yer imi başlığını değiştirir.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sTitle | String | Kaynak yer imi başlığı. |
| dTitle | String | Değiştirilmiş yer imi başlığı. |

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)