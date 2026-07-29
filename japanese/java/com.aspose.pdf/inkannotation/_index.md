---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "1 つ以上の切れ目のあるパスで構成されたフリーハンドの \\\"scribble\\\" を表します。"
type: docs
weight: 2430
url: /ja/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

1 本以上の切れ目のあるパスで構成されたフリーハンドの「落書き」を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Generator 用の Ink アノテーションのコンストラクタです。 |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | 指定されたページに新しい Ink アノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | マトリックス変換に従って InkList のポイントを更新します。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getCapStyle](#getCapStyle--) | Ink アノテーションのラインエンドのスタイルを取得します。 |
| [getInkList](#getInkList--) | <p> Point[] 配列で表される独立した線であるジェスチャのリストを取得します。 </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Ink アノテーションのラインエンドのスタイルを設定します。 |
| [setInkList](#setInkList-java.util.List-) | Point[] 配列で表される独立した線であるジェスチャのリストを設定します。 |
| [updateAppearance](#updateAppearance--) | テキストが変更/移動された後、外観を更新します。 |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Generator 用の Ink アノテーションのコンストラクタです。

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
指定されたページに新しい Ink アノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
マトリックス変換に従って InkList のポイントを更新します。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

Ink アノテーションのラインエンドのスタイルを取得します。

**Returns:**
CapStyle 要素 @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Point[] 配列で表される独立した線であるジェスチャのリストを取得します。 </p>

**Returns:**
{@code List<Point[]>} オブジェクト

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Ink アノテーションのラインエンドのスタイルを設定します。

### setInkList {#setInkList-java.util.List-}
Point[] 配列で表される独立した線であるジェスチャのリストを設定します。

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

テキストが変更/移動された後、外観を更新します。
