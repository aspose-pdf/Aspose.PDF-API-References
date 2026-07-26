---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "グラフィック要素のコンテナクラスを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

グラフィック要素のコンテナクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | グラフィック要素用のコンテナクラスのインスタンスを作成します。 |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | グラフィック要素用のコンテナクラスのインスタンスを作成します。 |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | グラフィック要素用のコンテナクラスのインスタンスを作成します。 |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | グラフィック要素用のコンテナクラスのインスタンスを作成します。 |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | グラフィック要素用のコンテナクラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | 2つのコンテナ間の距離を計算します。 |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | 現在の SubPathContainer オブジェクトを別の SubPathContainer オブジェクトと比較し、現在のオブジェクトが他のオブジェクトより小さいか、等しいか、または大きいかを示す整数を返します。オブジェクトは数値 ID で比較されます。 |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | このコンテナと他のコンテナ間の距離を計算します。 |
| [getGraphElement](#getGraphElement--) | 含まれるグラフィック要素を取得します。 |
| [getId](#getId--) | SubPathContainer の Id を取得します。Id はデバッグを容易にし、レンダリング中の要素のソートに必要です。 |
| [getRect](#getRect--) | 含まれる要素の矩形を表します。 |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

グラフィック要素用のコンテナクラスのインスタンスを作成します。

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
グラフィック要素用のコンテナクラスのインスタンスを作成します。

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
グラフィック要素用のコンテナクラスのインスタンスを作成します。

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
グラフィック要素用のコンテナクラスのインスタンスを作成します。

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
グラフィック要素用のコンテナクラスのインスタンスを作成します。

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
2つのコンテナ間の距離を計算します。

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
現在の SubPathContainer オブジェクトを別の SubPathContainer オブジェクトと比較し、現在のオブジェクトが他のオブジェクトより小さいか、等しいか、または大きいかを示す整数を返します。オブジェクトは数値 ID で比較されます。

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
このコンテナと他のコンテナ間の距離を計算します。

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

含まれるグラフィック要素を取得します。

**Returns:**
GraphicElement インスタンス

### getId {#getId--}
```
public final int getId()
```

SubPathContainer の Id を取得します。Id はデバッグを容易にし、レンダリング中の要素のソートに必要です。

**Returns:**
int 値です。

### getRect {#getRect--}
```
public final Rectangle getRect()
```

含まれる要素の矩形を表します。

**Returns:**
矩形インスタンス

### toString {#toString--}
```
public String toString()
```

{@code }
