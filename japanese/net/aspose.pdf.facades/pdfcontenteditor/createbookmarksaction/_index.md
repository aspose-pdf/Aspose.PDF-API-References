---
title: "PdfContentEditor.CreateBookmarksAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。指定されたアクションでブックマークを作成します"
type: docs
weight: 120
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

指定されたアクションを持つブックマークを作成します。

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| title | String | ブックマークのタイトルです。 |
| color | Color | ブックマークのタイトルの色です。 |
| boldFlag | Boolean | 太字属性のフラグです。 |
| italicFlag | Boolean | 斜体属性のフラグです。 |
| file | String | アクションタイプが "GoToR" または "Launch" の場合に必要な別のファイルまたはアプリケーションです。 |
| actionType | String | アクションタイプです。値は次のいずれかです: "GoToR", "Launch", "GoTo", "URI"。 |
| destination | String | ローカルの宛先、リモートの宛先、または URL です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


