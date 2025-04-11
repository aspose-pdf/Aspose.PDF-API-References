---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。キャレット注釈を作成します。
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret メソッド

キャレット注釈を作成します。

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Int32 | 注釈が作成される元のページの番号。 |
| annotRect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| caretRect | Rectangle | 基本となるキャレットの実際の境界。 |
| symbol | String | キャレットに関連付けられるシンボル。値は「P」（段落）または「None」です。 |
| annotContents | String | 注釈の内容。 |
| color | Color | 注釈の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)