---
title: "PdfContentEditor.ReplaceImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメントの指定ページ上の指定画像を別の画像に置き換えます。"
type: docs
weight: 440
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

PDFドキュメントの指定されたページ上の指定された画像を別の画像に置き換えます。

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 画像が置き換えられるページの番号。 |
| インデックス | Int32 | 置き換える画像オブジェクトのインデックス。 |
| imageFile | String | 置き換えに使用される画像ファイル。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


