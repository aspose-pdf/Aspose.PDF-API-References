---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin 列挙型。ラインジョインスタイルは、ストロークされたパスのコーナーで使用される形状を指定します。
type: docs
weight: 7450
url: /ja/net/aspose.pdf.operators/linejoin/
---
## LineJoin 列挙型

ラインジョインスタイルは、ストロークされたパスのコーナーで使用される形状を指定します。

```csharp
public enum LineJoin
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| MiterJoin | `0` | ミタージョイン。2つのセグメントのストロークの外側のエッジは、絵画のフレームのように角度で出会うまで延長されます。セグメントがミタリミットパラメータで定義された角度であまりにも鋭く出会う場合（8.4.3.5「ミタリミット」を参照）、代わりにベベルジョインが使用されます。 |
| RoundJoin | `1` | ラウンドジョイン。2つのセグメントが出会う点の周りに、ライン幅と同じ直径の円弧が描かれ、2つのセグメントのストロークの外側のエッジを接続します。このパイのスライスの形をした図形は塗りつぶされ、丸みを帯びたコーナーを生成します。 |
| BevelJoin | `2` | ベベルジョイン。2つのセグメントはバットキャップ（8.4.3.3「ラインキャップスタイル」を参照）で仕上げられ、セグメントの端を超えた結果の切り欠きは三角形で塗りつぶされます。 |

### 参照

* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)