---
title: "SubPath"
linktitle: "SubPath"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上のベクターグラフィックオブジェクトを表します。基本的に、ベクターグラフィックオブジェクトは 2 つの SubPath グループで表現されます。そのうちの一つは線の集合で表されます。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

ページ上のベクターグラフィックオブジェクトを表します。基本的に、ベクターグラフィックオブジェクトは 2 つの SubPath グループで表現されます。そのうちの一方は線と曲線の集合で表され、もう一方は矩形として提示され、時には混同されることがあります。通常、色を持つ矩形領域ですが、この矩形はページの先頭に配置され、ページ全体を白で覆うことが多いです。そのため SubPath は取得できますが、視覚的にはページ上のテキストのみが表示されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRectangle](#getRectangle--) | GraphicElement の境界矩形を取得します。 |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

GraphicElement の境界矩形を取得します。

**Returns:**
矩形インスタンス
