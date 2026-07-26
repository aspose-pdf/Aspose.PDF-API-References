---
title: "Element"
linktitle: "Element"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造内の要素の基底クラスを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element

```
public abstract class Element extends Object
```

論理構造内の要素の基底クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を追加します。 |
| [appendChild](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | 子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を追加します。 |
| [clearChilds](#clearChilds--) | すべての子要素をクリアします。 |
| [findElements](#findElements-java.lang.Class-) | 指定されたタイプの要素を検索します |
| [findElements](#findElements-java.lang.Class-boolean-) | 指定されたタイプの要素を検索します |
| [getChildElements](#getChildElements--) | {@code Element} オブジェクトの子コレクションを取得します。 |
| [getElementEngine](#getElementEngine--) | 親要素を取得します。 |
| [getParentElement](#getParentElement--) | {@code Element} オブジェクトの親コレクションを取得します。 |
| [getTaggedContent](#getTaggedContent--) |  |
| [getTrailer](#getTrailer--) | 内部メソッド |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | 指定されたインデックスで子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を挿入します。 |
| [insertChild](#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-) | 指定されたインデックスで子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を挿入します。 |
| [preSave](#preSave--) |  |
| [removeChild](#removeChild-int-) | 指定位置の子要素を削除。 |
| [setParentElement](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [tag](#tag-com.aspose.pdf.Annotation-) | 構造要素をアノテーションにバインドします。 |
| [tag](#tag-com.aspose.pdf.Artifact-) | 構造要素をアーティファクトにバインドします。 |
| [tag](#tag-com.aspose.pdf.operators.BDC-) | 構造要素をコンテンツストリームの BDC 演算子にバインドします。 |
| [tag](#tag-com.aspose.pdf.XForm-) | 構造要素をコンテンツストリームの XForm にバインドします。 |
| [tag](#tag-com.aspose.pdf.XImage-) | 構造要素を XImage にバインドします。 |
| [toString](#toString--) | 現在のオブジェクトを表す文字列を返します。 |

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を追加します。

### appendChild {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を追加します。

### clearChilds {#clearChilds--}
```
public final void clearChilds()
```

すべての子要素をクリアします。

### findElements {#findElements-java.lang.Class-}
指定されたタイプの要素を検索します

### findElements {#findElements-java.lang.Class-boolean-}
指定されたタイプの要素を検索します

### getChildElements {#getChildElements--}
```
public final ElementList getChildElements()
```

{@code Element} オブジェクトの子コレクションを取得します。

**Returns:**
値: {@code Element} オブジェクトの子要素コレクション。

### getElementEngine {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```

親要素を取得します。

**Returns:**
値: 親要素。

### getParentElement {#getParentElement--}
```
public final Element getParentElement()
```

{@code Element} オブジェクトの親コレクションを取得します。

**Returns:**
値: {@code Element} オブジェクトの親コレクション。

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```



### getTrailer {#getTrailer--}
```
public final com.aspose.pdf.engine.data.ITrailerable getTrailer()
```

内部メソッド

**Returns:**
内部要素

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
指定されたインデックスで子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を挿入します。

### insertChild {#insertChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-boolean-}
指定されたインデックスで子コレクションに {@code /Aspose.Pdf.LogicalStructure.Element} を挿入します。

### preSave {#preSave--}
```
public void preSave()
```



### removeChild {#removeChild-int-}
```
public final void removeChild(int index)
```

指定位置の子要素を削除。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 子要素インデックス。 |

### setParentElement {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


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
