---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。スクエアサークル注釈を作成します。
type: docs
weight: 280
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle メソッド

スクエアサークル注釈を作成します。

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈の矩形。 |
| contents | String | 注釈の内容。 |
| clr | Color | スクエアまたはサークルの色。 |
| square | Boolean | 真（スクエア）、偽（サークル）。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| borderWidth | Int32 | スクエアまたはサークルの境界線の幅。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)