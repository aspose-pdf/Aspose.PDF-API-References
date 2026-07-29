---
title: "ITociElement"
linktitle: "ITociElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "タグ付けされた PDF ドキュメントにおいて目次エントリ (TOCI) として機能できる要素を表します。このインターフェイスは標準的な TOCI 要素とリスト項目 (LI) の両方を抽象化します。"
type: docs
weight: 80
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.grouping/itocielement/
---
```
public interface ITociElement
```

タグ付けされたPDFドキュメントにおいて目次エントリ（TOCI）として機能できる要素を表します。このインターフェイスは、標準的なTOCI要素と、入れ子になった目次構造で使用されるリスト項目（LI）要素の両方を抽象化します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getGetElement](#getGetElement--) | この TOCI 構造を表す基礎となる PDF 要素を取得します。 |

### getGetElement {#getGetElement--}
```
StructureElement getGetElement()
```

この TOCI 構造を表す基礎となる PDF 要素を取得します。

**Returns:**
この目次エントリの構造表現を形成する Element。
