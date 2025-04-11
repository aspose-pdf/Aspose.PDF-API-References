---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。曲線注釈を作成します。
type: docs
weight: 360
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve メソッド

曲線注釈を作成します。

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lineInfo | LineInfo | LineInfo クラスのインスタンス。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| annotRect | Rectangle | ページ上の注釈の位置を定義する注釈矩形。 |
| annotContents | String | 注釈の内容。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### 参照

* クラス [LineInfo](../../lineinfo/)
* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)