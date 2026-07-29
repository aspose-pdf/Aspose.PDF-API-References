---
title: "MCRElement"
linktitle: "MCRElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造におけるマークドコンテンツ参照オブジェクトを表します。"
type: docs
weight: 80
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.MCRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.MCRElement

```
public final class MCRElement extends Element
```

論理構造におけるマークドコンテンツ参照オブジェクトを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Handler](#Handler) |  |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MCRElement](#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMCID](#getMCID--) | マークドコンテンツ参照オブジェクトの MCID を取得します。 |
| [getPage](#getPage--) | ページインスタンスを取得 |
| [preSave](#preSave--) |  |
| [setNewMCID](#setNewMCID-int-) | MCID 値を取得 |
| [setPage](#setPage-com.aspose.pdf.Page-) | ページインスタンスを設定 |
| [tag](#tag-com.aspose.pdf.Annotation-) | 構造要素をアノテーションにバインドします。 |
| [tag](#tag-com.aspose.pdf.Artifact-) | 構造要素をアーティファクトにバインドします。 |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | 構造要素をコンテンツストリームの BDC 演算子にバインドします。 |
| [tag](#tag-com.aspose.pdf.XForm-) | 構造要素をコンテンツストリームの XForm にバインドします。 |
| [tag](#tag-com.aspose.pdf.XImage-) | 構造要素を XImage にバインドします。 |
| [toString](#toString--) | 現在のオブジェクトを表す文字列を返します。 |

### Handler {#Handler}
```
public com.aspose.pdf.tagged.helpers.logicalstructure.MCRElementHandler Handler
```



### MCRElement {#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
コンストラクタ

### getMCID {#getMCID--}
```
public final int getMCID()
```

マークドコンテンツ参照オブジェクトの MCID を取得します。

**Returns:**
マークドコンテンツ参照オブジェクトの MCID。

### getPage {#getPage--}
```
public final Page getPage()
```

ページインスタンスを取得

**Returns:**
ページインスタンス

### preSave {#preSave--}
```
public void preSave()
```



### setNewMCID {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```

MCID 値を取得

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | MCID 値 |

### setPage {#setPage-com.aspose.pdf.Page-}
ページインスタンスを設定

### tag {#tag-com.aspose.pdf.Annotation-}
構造要素をアノテーションにバインドします。

### tag {#tag-com.aspose.pdf.Artifact-}
構造要素をアーティファクトにバインドします。

### tag {#tag-com.aspose.pdf.operators.BDC-}
構造要素をコンテンツストリームの BDC 演算子にバインドします。

### tag {#tag-com.aspose.pdf.XForm-}
構造要素をコンテンツストリームの XForm にバインドします。

### tag {#tag-com.aspose.pdf.XImage-}
構造要素を XImage にバインドします。

### toString {#toString--}
```
public String toString()
```

現在のオブジェクトを表す文字列を返します。

**Returns:**
現在のオブジェクトを表す文字列。
