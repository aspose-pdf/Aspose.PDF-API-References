---
title: "PdfContentEditor.CreateFreeText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF Document にフリーテキスト注釈を作成します。"
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

PDF ドキュメントにフリーテキスト注釈を作成します

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| contents | String | アノテーションの内容です。 |
| ページ | Int32 | テキスト注釈が作成される元の Page 番号です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


