---
title: "PdfContentEditor.CreateText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメントにテキストアノテーションを作成します"
type: docs
weight: 290
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

PDFドキュメントにテキスト注釈を作成します

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| title | String | アノテーションのタイトルです。 |
| contents | String | アノテーションの内容です。 |
| open | Boolean | 注釈が最初に開いた状態で表示されるかどうかを指定するフラグです。 |
| icon | String | 注釈の表示に使用されるアイコンの名前です。この値は次のいずれかにできます: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| ページ | Int32 | テキスト注釈が作成される元の Page 番号です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


