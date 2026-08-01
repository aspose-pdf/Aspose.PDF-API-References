---
title: "PdfContentEditor.CreateLine"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。ライン注釈を作成します"
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

線注釈を作成します。

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上でアノテーションの位置を定義するアノテーション矩形です。 |
| contents | String | アノテーションの内容です。 |
| x1 | Single | ラインの開始水平座標。 |
| y1 | Single | 線の開始垂直座標。 |
| x2 | Single | 線の終了水平座標。 |
| y2 | Single | 線の終了垂直座標。 |
| ページ | Int32 | アノテーションが作成される元のページ番号です。 |
| border | Int32 | 境界線の幅（ポイント単位）。この値が 0 の場合、境界線は描画されません。デフォルト値は 1 です。 |
| clr | Color | 線の色。 |
| borderStyle | String | 線の描画に使用する幅と破線パターンを指定する境界線スタイル。この値は次のいずれかです: "S"（実線）、"D"（破線）、"B"（ベベル）、"I"（インセット）、"U"（下線）。 |
| dashArray | Int32[] | 破線境界線の描画に使用する破線と間隔のパターンを定義するダッシュ配列。使用する場合、borderStyle を "D" に設定する必要があります。 |
| LEArray | String[] | 描画線の開始スタイルと終了スタイルをそれぞれ指定する 2 つの値の配列。値は次のいずれかです: "Square"、"Circle"、"Diamond"、"OpenArrow"、"ClosedArrow"、"None"、"Butt"、"ROpenArrow"、"RClosedArrow"、"Slash"。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


