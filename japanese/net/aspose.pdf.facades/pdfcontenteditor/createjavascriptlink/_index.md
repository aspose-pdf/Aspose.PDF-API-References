---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメント内の JavaScript へのリンクを作成します。
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink メソッド

PDF ドキュメント内の JavaScript へのリンクを作成します。

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| code | String | JavaScript コード。 |
| rect | Rectangle | アクティブクリック用の矩形。 |
| originalPage | Int32 | リンクと結びつけられた矩形が作成される元のページの番号。 |
| color | Color | アクティブクリック用の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)