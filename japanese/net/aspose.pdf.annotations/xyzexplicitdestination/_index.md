---
title: "クラス XYZExplicitDestination"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination クラス。ウィンドウの左上隅に配置された left top 座標でページを表示し、ページの内容をズーム係数で拡大する明示的な宛先を表します。left、top、または zoom のいずれかのパラメータに null 値を指定すると、そのパラメータの現在の値が変更されずに保持されます。ズーム値が 0 の場合は null 値と同じ意味です。"
type: docs
weight: 2830
url: /ja/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

ウィンドウの左上隅に (left, top) の座標でページを表示し、ページの内容を zoom 倍率で拡大する明示的なデスティネーションを表します。left、top、または zoom のいずれかのパラメータが null の場合、そのパラメータの現在の値は変更されずに保持されます。zoom 値が 0 の場合は null と同じ意味です。

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | リモートの明示的デスティネーションを作成します。 |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | ローカルの明示的デスティネーションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | ウィンドウの左上隅の左水平座標を取得します。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | デスティネーションの Page オブジェクトを取得します。 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | デスティネーションの Page 番号を取得します。 |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | ウィンドウの左上隅の上垂直座標を取得します。 |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | ズーム係数を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | 必要に応じてページの回転を考慮し、ページの指定された位置への宛先を作成します。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | 指定されたページへの宛先を作成します。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | 指定されたページの左上隅への宛先を作成します。 |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | オブジェクトの状態を文字列値に変換します。例: "1 XYZ 100 200 3"。 |

## 例

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### 関連項目

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


