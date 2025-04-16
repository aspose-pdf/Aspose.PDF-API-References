---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XYZExplicitDestination クラス。ウィンドウの左上隅に位置する座標 （left, top） でページを表示し、ページの内容をズームファクターで拡大表示する明示的な目的地を表します。left、top、または zoom のいずれかのパラメーターに対して null 値が指定されると、そのパラメーターの現在の値が変更されずに保持されることを指定します。ズーム値が 0 の場合は、null 値と同じ意味を持ちます。
type: docs
weight: 2730
url: /ja/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination クラス

ウィンドウの左上隅に位置する座標 (left, top) でページを表示し、ページの内容をズームファクターで拡大表示する明示的な目的地を表します。left、top、または zoom のいずれかのパラメーターに対して null 値が指定されると、そのパラメーターの現在の値が変更されずに保持されることを指定します。ズーム値が 0 の場合は、null 値と同じ意味を持ちます。

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | リモート明示的目的地を作成します。 |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | ローカル明示的目的地を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | ウィンドウの左上隅の左水平座標を取得します。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 目的地ページオブジェクトを取得します。 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 目的地ページ番号を取得します。 |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | ウィンドウの左上隅の上垂直座標を取得します。 |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | ズームファクターを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | 必要に応じてページの回転を考慮して、指定された位置に目的地を作成します。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | 指定されたページに目的地を作成します。 |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | 指定されたページの左上隅に目的地を作成します。 |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | オブジェクトの状態を文字列値に変換します。例: "1 XYZ 100 200 3"。 |

## 例

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### 参照

* クラス [ExplicitDestination](../explicitdestination/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)