---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントにテキスト注釈を作成します
type: docs
weight: 290
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText メソッド

PDF ドキュメントにテキスト注釈を作成します

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| title | String | 注釈のタイトル。 |
| contents | String | 注釈の内容。 |
| open | Boolean | 注釈が最初に表示されるときに開いているかどうかを指定するフラグ。 |
| icon | String | 注釈を表示する際に使用されるアイコンの名前。この値は次のいずれかです: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | Int32 | テキスト注釈が作成される元のページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)