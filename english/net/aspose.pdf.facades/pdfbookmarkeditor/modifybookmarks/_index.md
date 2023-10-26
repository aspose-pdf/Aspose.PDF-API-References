---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor method. Modifys bookmark title according to the specified bookmark title
type: docs
weight: 80
url: /net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

Modifys bookmark title according to the specified bookmark title.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sTitle | String | Source bookmark title. |
| dTitle | String | Modified bookmark title. |

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


