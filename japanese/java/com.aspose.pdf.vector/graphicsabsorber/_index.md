---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "グラフィック要素の吸収オブジェクトを表します。グラフィック検索を実行し、検索結果へ {@code GraphicsAbsorber.Elements}（{@link を介してアクセスできるようにします。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

グラフィック要素の吸収オブジェクトを表します。グラフィック検索を実行し、{@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}) コレクションを介して検索結果へのアクセスを提供します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [dispose](#dispose--) | {@link GraphicsAbsorber} クラスが使用するすべてのリソースを解放します。 |
| [getElements](#getElements--) | {@link GraphicElement} オブジェクトで表される検索結果のコレクションを取得します。 |
| [resumeUpdate](#resumeUpdate--) | Page#getContents とすべての @link XForm#getContents の更新を再開します。パフォーマンス向上のために行われました。詳細は参照してください。 |
| [suppressUpdate](#suppressUpdate--) | Page#getContents とすべての @link XForm#getContents の更新を抑制します。パフォーマンス向上のために行われました。詳細は参照してください。 |
| [visit](#visit-com.aspose.pdf.Page-) | 指定されたページで検索を実行します。 |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

{@link GraphicsAbsorber} クラスが使用するすべてのリソースを解放します。

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

{@link GraphicElement} オブジェクトで表される検索結果のコレクションを取得します。

**Returns:**
GraphicElementCollection インスタンス

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Page#getContents とすべての @link XForm#getContents の更新を再開します。パフォーマンス向上のために行われました。詳細は参照してください。

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Page#getContents とすべての @link XForm#getContents の更新を抑制します。パフォーマンス向上のために行われました。詳細は参照してください。

### visit {#visit-com.aspose.pdf.Page-}
指定されたページで検索を実行します。
