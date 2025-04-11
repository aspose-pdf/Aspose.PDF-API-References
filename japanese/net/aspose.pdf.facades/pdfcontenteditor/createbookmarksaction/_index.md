---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。指定されたアクションでブックマークを作成します。
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction メソッド

指定されたアクションでブックマークを作成します。

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| title | String | ブックマークのタイトル。 |
| color | Color | ブックマークのタイトルの色。 |
| boldFlag | Boolean | 太字属性のフラグ。 |
| italicFlag | Boolean | イタリック属性のフラグ。 |
| file | String | アクションタイプが "GoToR" または "Launch" の場合に必要な別のファイルまたはアプリケーション。 |
| actionType | String | アクションタイプ。値は次のいずれかです: "GoToR", "Launch", "GoTo", "URI"。 |
| destination | String | ローカルの宛先またはリモートの宛先または URL。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)