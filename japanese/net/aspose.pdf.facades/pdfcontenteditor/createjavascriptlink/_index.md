---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメント内の JavaScript へのリンクを作成します。"
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

PDF ドキュメント内の JavaScript へのリンクを作成します。

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| コード | String | この JavaScript コードです。 |
| rect | Rectangle | クリック可能な領域の矩形。 |
| originalPage | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |
| color | Color | クリック可能な領域の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


