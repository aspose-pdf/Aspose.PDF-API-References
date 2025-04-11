---
title: PdfContentEditor.CreatePolyLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。ポリライン注釈を作成します。
type: docs
weight: 240
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## PdfContentEditor.CreatePolyLine メソッド

ポリライン注釈を作成します。

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### 参照

* クラス [LineInfo](../../lineinfo/)
* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)