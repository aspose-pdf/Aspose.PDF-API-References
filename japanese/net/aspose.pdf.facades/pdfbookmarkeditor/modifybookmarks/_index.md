---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfBookmarkEditor メソッド。指定されたブックマークタイトルに従ってブックマークのタイトルを変更します"
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

指定されたブックマークタイトルに従ってブックマークのタイトルを変更します。

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| sTitle | String | 元のブックマークタイトル。 |
| dTitle | String | 変更後のブックマークタイトル。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


