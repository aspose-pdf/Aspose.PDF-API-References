---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "文書内の別の場所へのハイパーリンク、または実行されるアクションのいずれかを表します。"
type: docs
weight: 2760
url: /ja/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

文書内の別の場所へのハイパーリンク、または実行されるアクションのいずれかを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 指定されたページに新しい Link アノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [getAction](#getAction--) | リンクアノテーションが有効化されたときに実行されるアクションを取得します。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getDestination](#getDestination--) | アノテーションが有効化されたときに表示される宛先を取得します。 |
| [getHighlighting](#getHighlighting--) | マウスボタンがアクティブ領域内で押されたり長押しされたりしたときに使用されるビジュアルエフェクトを取得します。 |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | リンクアノテーションが有効化されたときに実行されるアクションを設定します。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | アノテーションが有効化されたときに表示される宛先を設定します。 |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | マウスボタンがアクティブ領域内で押されたり長押しされたりしたときに使用されるビジュアルエフェクトを設定します。 |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
指定されたページに新しい Link アノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### getAction {#getAction--}
```
public PdfAction getAction()
```

リンクアノテーションが有効化されたときに実行されるアクションを取得します。

**Returns:**
PdfAction 値

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

アノテーションが有効化されたときに表示される宛先を取得します。

**Returns:**
IAppointment 値

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

マウスボタンがアクティブ領域内で押されたり長押しされたりしたときに使用されるビジュアルエフェクトを取得します。

**Returns:**
HighlightingMode 要素 @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
リンクアノテーションが有効化されたときに実行されるアクションを設定します。

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
アノテーションが有効化されたときに表示される宛先を設定します。

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
マウスボタンがアクティブ領域内で押されたり長押しされたりしたときに使用されるビジュアルエフェクトを設定します。
