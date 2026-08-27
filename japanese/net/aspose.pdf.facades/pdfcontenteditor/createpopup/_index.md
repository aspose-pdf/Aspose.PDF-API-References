---
title: "PdfContentEditor.CreatePopup"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメントにポップアップ注釈を作成します。"
type: docs
weight: 250
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

PDFドキュメントにポップアップ注釈を作成します。

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| contents | String | アノテーションの内容です。 |
| open | Boolean | ポップアップ注釈を最初に開いた状態で表示するかどうかを指定するフラグです。 |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


