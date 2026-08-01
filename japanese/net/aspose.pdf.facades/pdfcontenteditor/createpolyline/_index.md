---
title: "PdfContentEditor.CreatePolyLine"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。ポリライン注釈を作成します"
type: docs
weight: 240
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## PdfContentEditor.CreatePolyLine method

ポリライン注釈を作成します。

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### 関連項目

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


