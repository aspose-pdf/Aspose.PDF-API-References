---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。指定された PDF ドキュメントの指定されたページの画像を別の画像に置き換えます
type: docs
weight: 440
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage メソッド

指定された PDF ドキュメントの指定されたページの画像を別の画像に置き換えます。

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 画像が置き換えられるページの番号。 |
| index | Int32 | 置き換える必要がある画像オブジェクトのインデックス。 |
| imageFile | String | 置き換えに使用される画像ファイル。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)