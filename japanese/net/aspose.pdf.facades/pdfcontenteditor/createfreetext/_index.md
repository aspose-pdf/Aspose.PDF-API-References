---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントに自由テキスト注釈を作成します
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText メソッド

PDF ドキュメントに自由テキスト注釈を作成します

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| contents | String | 注釈の内容。 |
| page | Int32 | テキスト注釈が作成される元のページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)