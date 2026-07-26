---
title: "ScreenAnnotation"
linktitle: "ScreenAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "メディアクリップを再生できるページ上の領域を指定するスクリーン注釈。"
type: docs
weight: 4470
url: /ja/java/com.aspose.pdf/screenannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.ScreenAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class ScreenAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

メディアクリップを再生できるページ上の領域を指定するスクリーン注釈。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ScreenAnnotation](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | 指定されたページに新しい Screen アノテーションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | accept メソッドを表します |
| [getAction](#getAction--) | アノテーションがアクティブ化されたときに実行されるアクションを取得します。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getTitle](#getTitle--) | Screen アノテーションのタイトルを取得します。 |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | アノテーションがアクティブ化されたときに実行されるアクションを設定します。 |
| [setTitle](#setTitle-java.lang.String-) | 画面注釈のタイトルを設定します。 |

### ScreenAnnotation {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
指定されたページに新しい Screen アノテーションを作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
accept メソッドを表します

### getAction {#getAction--}
```
public PdfAction getAction()
```

アノテーションがアクティブ化されたときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素 @see AnnotationType

### getTitle {#getTitle--}
```
public String getTitle()
```

Screen アノテーションのタイトルを取得します。

**Returns:**
文字列値

### setAction {#setAction-com.aspose.pdf.PdfAction-}
アノテーションがアクティブ化されたときに実行されるアクションを設定します。

### setTitle {#setTitle-java.lang.String-}
画面注釈のタイトルを設定します。
