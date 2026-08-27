---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストマークアップ注釈の抽象基底クラスです。"
type: docs
weight: 5180
url: /ja/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

テキストマークアップ注釈の抽象基底クラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | QuadPoints を、行列変換に従って更新します。 |
| [getMarkedText](#getMarkedText--) | マークアップ注釈の下のテキストを文字列として取得します。 |
| [getMarkedTextFragments](#getMarkedTextFragments--) | マークアップ注釈の下のテキストを {@code TextFragmentCollection} として取得します。 |
| [getQuadPoints](#getQuadPoints--) | n 個の四辺形の座標を指定するポイントの配列を取得します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。 |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | n 個の四辺形の座標を指定するポイントの配列を設定します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。 |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
QuadPoints を、行列変換に従って更新します。

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

マークアップ注釈の下のテキストを文字列として取得します。

**Returns:**
マークアップ注釈の下にあるテキストを含む文字列です。

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

マークアップ注釈の下のテキストを {@code TextFragmentCollection} として取得します。

**Returns:**
マークアップ注釈の下にある {@code TextFragment}s を含む {@code TextFragmentCollection} です。

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

n 個の四辺形の座標を指定するポイントの配列を取得します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。

**Returns:**
Point 値の配列

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
n 個の四辺形の座標を指定するポイントの配列を設定します。各四辺形は、注釈の下にあるテキスト内の単語または連続した単語のグループを包含します。
