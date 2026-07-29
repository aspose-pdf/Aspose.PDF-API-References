---
title: "BLSTextElement"
linktitle: "BLSTextElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造におけるブロックレベルテキスト構造要素の基底クラスを表します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSTextElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class BLSTextElement extends BLSElement implements ITextElement , IAdjustPosition
```

論理構造におけるブロックレベルテキスト構造要素の基底クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 位置を調整します。 |
| [getStructureTextState](#getStructureTextState--) | 現在の要素の {@code StructureTextState} オブジェクトを取得します。値: 現在の要素の {@code structureTextState} オブジェクトです。 |
| [getTextFragment](#getTextFragment--) |  |
| [setText](#setText-java.lang.String-) | 現在のテキスト要素にテキストコンテンツを追加します。 |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
位置を調整します。

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

現在の要素の {@code StructureTextState} オブジェクトを取得します。値: 現在の要素の {@code structureTextState} オブジェクトです。

**Returns:**
値: テキスト構造要素の StructureTextState オブジェクト。

### getTextFragment {#getTextFragment--}
```
public final TextFragment getTextFragment()
```



### setText {#setText-java.lang.String-}
現在のテキスト要素にテキストコンテンツを追加します。
