---
title: "PdfContentEditor.CreateCaret"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。キャレット注釈を作成します。"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret method

キャレット注釈を作成します。

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| annotRect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| caretRect | Rectangle | 基になるキャレットの実際の境界です。 |
| シンボル | String | キャレットにシンボルが関連付けられます。値は "P"（段落）または "None" にできます。 |
| annotContents | String | アノテーションの内容です。 |
| color | Color | アノテーションの色です。 |

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


