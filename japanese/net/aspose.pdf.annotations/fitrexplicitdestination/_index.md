---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FitRExplicitDestination クラス。指定された座標の左、下、右、上によって指定された矩形に収まるように、ページの内容が拡大表示される明示的な目的地を表します。必要な水平方向および垂直方向の拡大率が異なる場合は、2つのうち小さい方を使用し、他の次元でウィンドウ内に矩形を中央に配置します。パラメータのいずれかに null 値があると、予測不可能な動作が発生する可能性があります。
type: docs
weight: 1780
url: /ja/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination クラス

指定された座標の左、下、右、上によって指定された矩形に収まるように、ページの内容が拡大表示される明示的な目的地を表します。必要な水平方向および垂直方向の拡大率が異なる場合は、2つのうち小さい方を使用し、他の次元でウィンドウ内に矩形を中央に配置します。パラメータのいずれかに null 値があると、予測不可能な動作が発生する可能性があります。

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | リモート明示的目的地を作成します。 |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | ローカル明示的目的地を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | 可視矩形の下部垂直座標を取得します。 |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | 可視矩形の左部水平方向座標を取得します。 |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 目的地ページオブジェクトを取得します。 |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 目的地ページ番号を取得します。 |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | 可視矩形の右部水平方向座標を取得します。 |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | 可視矩形の上部垂直座標を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | オブジェクトの状態を文字列値に変換します。例: "1 FitR 100 200 300 400"。 |

### 参照

* クラス [ExplicitDestination](../explicitdestination/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)