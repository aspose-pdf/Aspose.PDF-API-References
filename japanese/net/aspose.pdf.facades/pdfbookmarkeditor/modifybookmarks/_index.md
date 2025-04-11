---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor メソッド。指定されたブックマークタイトルに従ってブックマークタイトルを変更します。
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks メソッド

指定されたブックマークタイトルに従ってブックマークタイトルを変更します。

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sTitle | String | ソースブックマークタイトル。 |
| dTitle | String | 変更されたブックマークタイトル。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfBookmarkEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)