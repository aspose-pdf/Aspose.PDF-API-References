---
title: Class SetGlyphsPositionShowText
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetGlyphsPositionShowText クラス。グリフ位置決定を伴うテキスト表示の TJ 演算子を表すクラス
type: docs
weight: 7710
url: /ja/net/aspose.pdf.operators/setglyphspositionshowtext/
---
## SetGlyphsPositionShowText クラス

TJ 演算子（グリフ位置決定を伴うテキスト表示）を表すクラスです。

```csharp
public class SetGlyphsPositionShowText : TextShowOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SetGlyphsPositionShowText](setglyphspositionshowtext/)(IEnumerable&lt;GlyphPosition&gt;) | TJ 演算子のコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [GlyphPositions](../../aspose.pdf.operators/setglyphspositionshowtext/glyphpositions/) { get; } | グリフの位置を返します。 |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページ演算子リスト内の演算子インデックス。 |
| override [Text](../../aspose.pdf.operators/setglyphspositionshowtext/text/) { get; } | 演算子引数からテキストを取得します（グリフ位置決定は無視されます）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setglyphspositionshowtext/accept/)(IOperatorSelector) | 演算子を処理するためのビジターオブジェクトを受け入れます。 |
| override [ToString](../../aspose.pdf.operators/setglyphspositionshowtext/tostring/)() | 演算子のテキスト表現を返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [TextShowOperator](../textshowoperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)