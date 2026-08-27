---
title: "列挙型 LineJoin"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Operators.LineJoin 列挙型。線の結合スタイルは、ストロークされたパスの角で使用される形状を指定します"
type: docs
weight: 7590
url: /ja/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

線のジョインスタイルは、ストロークされたパスの角部で使用される形状を指定します。

```csharp
public enum LineJoin
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| MiterJoin | `0` | マイター結合。2 つのセグメントのストロークの外側エッジは、額縁のように角度で交わるまで延長されます。セグメントがマイターリミット パラメータで定義された過度に鋭い角度で交わる場合（8.4.3.5「Miter Limit」参照）、代わりにベベル結合が使用されます。 |
| RoundJoin | `1` | ラウンド結合。2 つのセグメントが交わる点の周囲に、線幅と同じ直径の円弧が描かれ、2 つのセグメントのストロークの外側エッジを接続します。このパイ形の図形は塗りつぶされ、丸みを帯びた角が生成されます。 |
| BevelJoin | `2` | ベベル結合。2 つのセグメントはバットキャップで終端され（8.4.3.3「Line Cap Style」参照）、セグメントの端部を超えた結果として生じる切り込みは三角形で塗りつぶされます。 |

### 関連項目

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


