---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "リストの論理構造における LI 構造要素を表します。"
type: docs
weight: 110
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

リストの論理構造における LI 構造要素を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | この目次項目 (TOCI) 要素内の指定された {@link StructureElement} への参照を追加します。通常、{@code ListLIElement} が入れ子になった目次のヘッダーとして使用される場合に利用されます。 |
| [getGetElement](#getGetElement--) | この TOCI 構造を表す基礎となる PDF 要素を取得します。 |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
この目次項目 (TOCI) 要素内の指定された {@link StructureElement} への参照を追加します。通常、{@code ListLIElement} が入れ子になった目次のヘッダーとして使用される場合に利用されます。

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

この TOCI 構造を表す基礎となる PDF 要素を取得します。

**Returns:**
この目次エントリの構造表現を形成する Element。

### preSave {#preSave--}
```
public void preSave()
```
