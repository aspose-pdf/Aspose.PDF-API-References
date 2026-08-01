---
title: "クラス FitRExplicitDestination"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.FitRExplicitDestination クラス。左、下、右、上の座標で指定された矩形がウィンドウ内に水平・垂直の両方で完全に収まるように、ページの内容をちょうど拡大表示する明示的なデスティネーションを表します。必要な水平拡大率と垂直拡大率が異なる場合は、2 つのうち小さい方を使用し、もう一方の次元で矩形をウィンドウの中央に配置します。パラメータのいずれかに null 値が指定されると、予測できない動作になる可能性があります。"
type: docs
weight: 1870
url: /ja/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class

左、下、右、上の座標で指定された矩形がウィンドウ内に水平・垂直の両方で完全に収まるように内容を拡大表示する明示的なデスティネーションを表します。必要な水平拡大率と垂直拡大率が異なる場合は、両者の小さい方を使用し、もう一方の次元で矩形をウィンドウの中央に配置します。任意のパラメータが null の場合、予測できない動作になる可能性があります。

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | リモートの明示的デスティネーションを作成します。 |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | ローカルの明示的デスティネーションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | 表示矩形の下側垂直座標を取得します。 |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | 表示矩形の左側水平座標を取得します。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | デスティネーションの Page オブジェクトを取得します。 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | デスティネーションの Page 番号を取得します。 |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | 表示矩形の右側水平座標を取得します。 |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | 表示矩形の上側垂直座標を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | オブジェクトの状態を文字列値に変換します。例: "1 FitR 100 200 300 400". |

### 関連項目

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


