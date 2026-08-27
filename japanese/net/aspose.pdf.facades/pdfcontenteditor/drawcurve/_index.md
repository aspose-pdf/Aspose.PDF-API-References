---
title: "PdfContentEditor.DrawCurve"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。曲線注釈を作成します。"
type: docs
weight: 360
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve method

曲線注釈を作成します。

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| lineInfo | LineInfo | LineInfo クラスのインスタンスです。 |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| annotRect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| annotContents | String | アノテーションの内容です。 |

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

### 関連項目

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


