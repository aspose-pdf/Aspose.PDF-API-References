---
title: "TOCIElement"
linktitle: "TOCIElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造内の TOCI 構造要素を表します。"
type: docs
weight: 140
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.grouping/tocielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.grouping.GroupingElement com.aspose.pdf.tagged.logicalstructure.elements.grouping.TOCIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.grouping.GroupingElement com.aspose.pdf.tagged.logicalstructure.elements.grouping.TOCIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.grouping.GroupingElement com.aspose.pdf.tagged.logicalstructure.elements.grouping.TOCIElement, com.aspose.pdf.tagged.logicalstructure.elements.grouping.GroupingElement, com.aspose.pdf.tagged.logicalstructure.elements.grouping.TOCIElement

**All Implemented Interfaces:**
ITociElement

```
public final class TOCIElement extends GroupingElement implements ITociElement
```

論理構造内の TOCI 構造要素を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TOCIElement](#TOCIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | 目次項目 (TOCI) 要素内の指定された構造要素への参照を追加します。 |
| [getGetElement](#getGetElement--) | この TOCI 構造を表す基礎となる PDF 要素を取得します。 |

### TOCIElement {#TOCIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
目次項目 (TOCI) 要素内の指定された構造要素への参照を追加します。

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

この TOCI 構造を表す基礎となる PDF 要素を取得します。

**Returns:**
この目次エントリの構造表現を形成する Element。
