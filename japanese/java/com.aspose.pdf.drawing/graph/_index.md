---
title: "グラフ"
linktitle: "グラフ"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "グラフ - グラフィックジェネレータ段落を表します。"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

グラフ - グラフィックジェネレータ段落を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Graph](#Graph--) | 内部使用のみ |
| [Graph](#Graph-double-double-) | 新しい {@link Graph} クラスのインスタンスを初期化します。 |
| [Graph](#Graph-float-float-) | 新しい {@code Graph} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone](#deepClone--) | グラフをクローンします。 |
| [getBorder](#getBorder--) | 境界線を取得します。 |
| [getGraphInfo](#getGraphInfo--) | グラフ情報（色、線幅など）を示す {@code GraphInfo} オブジェクトを取得します。 |
| [getHeight](#getHeight--) | グラフの高さを示す float 値を取得します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm とインチもサポートされています。例: GraphHeight=\"10cm\" または GraphHeight=\"5inch\"。 |
| [getLeft](#getLeft--) | テーブルの左座標を取得します。 |
| [getShapes](#getShapes--) | グラフ内のすべてのシェイプを示すコレクションを取得します。 |
| [getTitle](#getTitle--) | グラフのタイトルを示す文字列値を取得します。 |
| [getTop](#getTop--) | テーブルの上座標を取得します。 |
| [getWidth](#getWidth--) | グラフの幅を示す float 値を取得します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm とインチもサポートされています。例: GraphWidth=\"10cm\" または GraphWidth=\"5inch\"。 |
| [isChangePosition](#isChangePosition--) | 段落処理後に現在位置を変更するかどうかを取得します。（デフォルト true） |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 境界線を設定します。 |
| [setChangePosition](#setChangePosition-boolean-) | 段落処理後に現在位置を変更するかどうかを設定します。（デフォルト true） |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | グラフ情報（色、線幅など）を示す {@code GraphInfo} オブジェクトを取得または設定します。 |
| [setHeight](#setHeight-double-) | グラフの高さを示す float 値を設定します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm とインチもサポートされています。例: GraphHeight=\"10cm\" または GraphHeight=\"5inch\"。 |
| [setLeft](#setLeft-double-) | テーブルの左座標を設定します。 |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | グラフ内のすべてのシェイプを示すコレクションを設定します。 |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | グラフのタイトルを示す文字列値を設定します。 |
| [setTop](#setTop-double-) | テーブルの上端座標を設定します。 |
| [setWidth](#setWidth-double-) | グラフの幅を示す浮動小数点値を設定します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm と inch もサポートされています。例: GraphWidth="10cm" または GraphWidth="5inch"。 |

### Graph {#Graph--}
```
public Graph()
```

内部使用のみ

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

新しい {@link Graph} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | グラフの幅。 |
| 高さ |  | グラフの高さ。 |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

新しい {@code Graph} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | グラフの幅。 |
| 高さ |  | グラフの高さ。 |

### deepClone {#deepClone--}
```
public Object deepClone()
```

グラフをクローンします。

**Returns:**
クローンされたオブジェクト

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

境界線を取得します。

**Returns:**
BorderInfo 要素

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

グラフ情報（色、線幅など）を示す {@code GraphInfo} オブジェクトを取得します。

**Returns:**
GraphInfo オブジェクト

### getHeight {#getHeight--}
```
public double getHeight()
```

グラフの高さを示す float 値を取得します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm とインチもサポートされています。例: GraphHeight=\"10cm\" または GraphHeight=\"5inch\"。

**Returns:**
グラフの高さを示す値。

### getLeft {#getLeft--}
```
public double getLeft()
```

テーブルの左座標を取得します。

**Returns:**
テーブルの左側座標。

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

グラフ内のすべてのシェイプを示すコレクションを取得します。

**Returns:**
Shapes の BoundsCheckableList。

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

グラフのタイトルを示す文字列値を取得します。

**Returns:**
グラフのタイトル。

### getTop {#getTop--}
```
public double getTop()
```

テーブルの上座標を取得します。

**Returns:**
テーブルの上端座標。

### getWidth {#getWidth--}
```
public double getWidth()
```

グラフの幅を示す float 値を取得します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm とインチもサポートされています。例: GraphWidth=\"10cm\" または GraphWidth=\"5inch\"。

**Returns:**
グラフの幅を示す浮動小数点値。

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

段落処理後に現在位置を変更するかどうかを取得します。（デフォルト true）

**Returns:**
ブール値

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
境界線を設定します。

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

段落処理後に現在位置を変更するかどうかを設定します。（デフォルト true）

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
グラフ情報（色、線幅など）を示す {@code GraphInfo} オブジェクトを取得または設定します。

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

グラフの高さを示す float 値を設定します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm とインチもサポートされています。例: GraphHeight=\"10cm\" または GraphHeight=\"5inch\"。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | グラフの高さを示す。 |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

テーブルの左座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | テーブルの左側座標。 |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
グラフ内のすべてのシェイプを示すコレクションを設定します。

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
グラフのタイトルを示す文字列値を設定します。

### setTop {#setTop-double-}
```
public void setTop(double value)
```

テーブルの上端座標を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | テーブルの上端座標。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

グラフの幅を示す浮動小数点値を設定します。単位はポイントです。XML では、デフォルトの単位はポイントですが、cm と inch もサポートされています。例: GraphWidth="10cm" または GraphWidth="5inch"。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | グラフの幅を示す浮動小数点値。 |
