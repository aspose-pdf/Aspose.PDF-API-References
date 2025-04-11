---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。ライン注釈を作成します。
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine メソッド

ライン注釈を作成します。

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | ページ上の注釈の位置を定義する注釈の矩形。 |
| contents | String | 注釈の内容。 |
| x1 | Single | ラインの開始水平座標。 |
| y1 | Single | ラインの開始垂直座標。 |
| x2 | Single | ラインの終了水平座標。 |
| y2 | Single | ラインの終了垂直座標。 |
| page | Int32 | 注釈が作成される元のページの番号。 |
| border | Int32 | ポイント単位の境界線の幅。この値が 0 の場合、境界線は描画されません。デフォルト値は 1 です。 |
| clr | Color | ラインの色。 |
| borderStyle | String | ラインを描画する際に使用される幅とダッシュパターンを指定する境界線スタイル。この値は次のいずれかです: "S" (ソリッド)、"D" (ダッシュ)、"B" (ベベル)、"I" (インセット)、"U" (アンダーライン)。 |
| dashArray | Int32[] | ダッシュとギャップのパターンを定義するダッシュ配列。ダッシュ境界線を描画する際に使用されます。使用する場合、borderStyle は "D" に設定する必要があります。 |
| LEArray | String[] | 描画ラインの開始スタイルと終了スタイルをそれぞれ指定する二つの値の配列。値は次のいずれかです: "Square"、"Circle"、"Diamond"、"OpenArrow"、"ClosedArrow"、"None"、"Butt"、"ROpenArrow"、"RClosedArrow"、"Slash"。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)