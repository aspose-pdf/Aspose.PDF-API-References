---
title: "パス"
linktitle: "パス"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "弧を表します。"
type: docs
weight: 100
url: /ja/java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

弧を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Path](#Path--) | 新しい {@code Path} クラスのインスタンスを初期化します。 |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | 新しい {@code Path} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 項目が指定されたコンテナの寸法（境界を含む）に収まるかどうかをチェックします。 |
| [getShapes](#getShapes--) | <p> シェイプのコレクションを取得または設定します。 </p> |
| [getShapesInternal](#getShapesInternal--) | シェイプのコレクションを取得または設定します。 |

### Path {#Path--}
```
public Path()
```

新しい {@code Path} クラスのインスタンスを初期化します。

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
新しい {@code Path} クラスのインスタンスを初期化します。

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

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> シェイプのコレクションを取得または設定します。 </p>

**Returns:**
{@code java.util.List<Shape> }オブジェクト

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

シェイプのコレクションを取得または設定します。

**Returns:**
内部オブジェクト
