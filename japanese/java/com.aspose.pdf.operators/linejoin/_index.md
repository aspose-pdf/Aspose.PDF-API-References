---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "線のジョインスタイルは、ストロークされたパスの角部で使用される形状を指定するものとします。"
type: docs
weight: 370
url: /ja/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

線のジョインスタイルは、ストロークされたパスの角部で使用される形状を指定するものとします。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [BevelJoin](#BevelJoin) | ベベル結合。2 つのセグメントはバットキャップで終端され（8.4.3.3、\"Line Cap Style\" を参照）し、セグメントの端部を超えた結果の切り欠きは三角形で埋められます。 |
| [MiterJoin](#MiterJoin) | ミタージョイン。2 つのセグメントのストロークの外側エッジは、角度で交わるまで延長されます（絵枠のように）。セグメントがミタリミットパラメータで定義された過度に鋭い角度で交わる場合（8.4.3.5、\"Miter Limit\" を参照）、代わりにベベル結合が使用されます。 |
| [RoundJoin](#RoundJoin) | ラウンド結合。2 つのセグメントが交わる点の周囲に、線幅と同じ直径の円弧が描かれ、2 つのセグメントのストロークの外側エッジを接続します。このパイ形の図形は塗りつぶされ、丸みを帯びた角が生成されます。 |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

ベベル結合。2 つのセグメントはバットキャップで終端され（8.4.3.3、\"Line Cap Style\" を参照）し、セグメントの端部を超えた結果の切り欠きは三角形で埋められます。

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

ミタージョイン。2 つのセグメントのストロークの外側エッジは、角度で交わるまで延長されます（絵枠のように）。セグメントがミタリミットパラメータで定義された過度に鋭い角度で交わる場合（8.4.3.5、\"Miter Limit\" を参照）、代わりにベベル結合が使用されます。

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

ラウンド結合。2 つのセグメントが交わる点の周囲に、線幅と同じ直径の円弧が描かれ、2 つのセグメントのストロークの外側エッジを接続します。このパイ形の図形は塗りつぶされ、丸みを帯びた角が生成されます。
