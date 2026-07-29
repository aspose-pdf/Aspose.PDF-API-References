---
title: "楕円"
linktitle: "楕円"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "楕円を表します。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.drawing/ellipse/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Ellipse, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Ellipse

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Ellipse extends Shape
```

楕円を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Ellipse](#Ellipse--) | 内部使用のみ |
| [Ellipse](#Ellipse-double-double-double-double-) | 新しい {@code Ellipse} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getBottom](#getBottom--) | 楕円の下部位置を示す float 値を取得します。 |
| [getHeight](#getHeight--) | 楕円の高さを示す float 値を取得します。 |
| [getLeft](#getLeft--) | 楕円の左側位置を示す float 値を取得します。 |
| [getWidth](#getWidth--) | 楕円の幅を示す float 値を取得します。 |
| [setBottom](#setBottom-double-) | 楕円の下部位置を示す float 値を設定します。 |
| [setHeight](#setHeight-double-) | 楕円の高さを示す float 値を設定します。 |
| [setLeft](#setLeft-double-) | 楕円の左側位置を示す float 値を設定します。 |
| [setWidth](#setWidth-double-) | 楕円の幅を示す float 値を取得します。 |

### Ellipse {#Ellipse--}
```
public Ellipse()
```

内部使用のみ

### Ellipse {#Ellipse-double-double-double-double-}
```
public Ellipse(double left, double bottom, double width, double height)
```

新しい {@code Ellipse} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left |  | 楕円の左側位置です。 |
| bottom |  | 楕円の下部位置です。 |
| 幅 |  | 楕円の幅です。 |
| 高さ |  | 楕円の高さです。 |

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

### getBottom {#getBottom--}
```
public double getBottom()
```

楕円の下部位置を示す float 値を取得します。

**Returns:**
楕円の下部位置を示す値。

### getHeight {#getHeight--}
```
public double getHeight()
```

楕円の高さを示す float 値を取得します。

**Returns:**
楕円の高さを示す値

### getLeft {#getLeft--}
```
public double getLeft()
```

楕円の左側位置を示す float 値を取得します。

**Returns:**
楕円の左側位置を示す値です。

### getWidth {#getWidth--}
```
public double getWidth()
```

楕円の幅を示す float 値を取得します。

**Returns:**
楕円の幅を示す値です。

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

楕円の下部位置を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 楕円の下部位置を示す。 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

楕円の高さを示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 楕円の高さを示す |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

楕円の左側位置を示す float 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 楕円の左側位置を示す。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

楕円の幅を示す float 値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 楕円の幅を示す。 |
