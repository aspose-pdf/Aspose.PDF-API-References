---
title: "Shape"
linktitle: "Shape"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "形状 - 基本グラフィックオブジェクトを表します。"
type: docs
weight: 130
url: /ja/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

形状 - 基本グラフィックオブジェクトを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Shape](#Shape--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getGraphInfo](#getGraphInfo--) | グラフ情報（色、線幅など）を示すオブジェクトを取得します。 |
| [getText](#getText--) | シェイプのテキストを取得または設定します。 |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | グラフ情報（色、線幅など）を示すオブジェクトを設定します。 |
| [setText](#setText-com.aspose.pdf.TextFragment-) | シェイプのテキストを取得または設定します。 |

### Shape {#Shape--}
```
public Shape()
```



### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
適合する場合は true、そうでない場合は false。

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

グラフ情報（色、線幅など）を示すオブジェクトを取得します。

**Returns:**
グラフ情報を示すオブジェクト。

### getText {#getText--}
```
public TextFragment getText()
```

シェイプのテキストを取得または設定します。

**Returns:**
TextFragment オブジェクト

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
グラフ情報（色、線幅など）を示すオブジェクトを設定します。

### setText {#setText-com.aspose.pdf.TextFragment-}
シェイプのテキストを取得または設定します。
