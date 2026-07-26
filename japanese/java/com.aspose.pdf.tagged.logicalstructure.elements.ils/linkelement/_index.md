---
title: "LinkElement"
linktitle: "LinkElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "論理構造における Link 構造要素を表します。"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf.tagged.logicalstructure.elements.ils/linkelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.ILSElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.AnnotationElement, com.aspose.pdf.tagged.logicalstructure.elements.ils.LinkElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public final class LinkElement extends AnnotationElement implements ITextElement , IAdjustPosition
```

論理構造における Link 構造要素を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LinkElement](#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 位置を調整します。 |
| [getHyperlink](#getHyperlink--) | リンク要素のハイパーリンクを取得または設定します。 |
| [getStructureTextState](#getStructureTextState--) | 現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトを取得します。値: 現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトです。 |
| [preSave](#preSave--) |  |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | リンク要素のハイパーリンクを取得または設定します。 |
| [setText](#setText-java.lang.String-) | 現在のテキスト要素にテキストコンテンツを追加します。 |

### LinkElement {#LinkElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
位置を調整します。

### getHyperlink {#getHyperlink--}
```
public final Hyperlink getHyperlink()
```

リンク要素のハイパーリンクを取得または設定します。

**Returns:**
ハイパーリンク インスタンス

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトを取得します。値: 現在の要素の {@code /Aspose.Pdf.LogicalStructure.StructureTextState} オブジェクトです。

**Returns:**
値: テキスト構造要素の StructureTextState オブジェクト。

### preSave {#preSave--}
```
public void preSave()
```



### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
リンク要素のハイパーリンクを取得または設定します。

### setText {#setText-java.lang.String-}
現在のテキスト要素にテキストコンテンツを追加します。
