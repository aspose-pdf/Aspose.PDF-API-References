---
title: "PdfContentEditor.CreateSquareCircle"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。squarecircle アノテーションを作成します"
type: docs
weight: 280
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

四角形・円形注釈を作成します。

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| contents | String | アノテーションの内容です。 |
| clr | Color | 四角形または円の色です。 |
| 四角形 | Boolean | True (square)、false (sircle)。 |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| borderWidth | Int32 | 四角形または円の枠線幅です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


