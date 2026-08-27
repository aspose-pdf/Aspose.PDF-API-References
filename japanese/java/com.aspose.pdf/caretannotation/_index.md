---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Caretアノテーションを表すクラス。"
type: docs
weight: 470
url: /ja/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Caretアノテーションを表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Generator で使用するコンストラクタ。 |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 指定されたページに新しい Caret 注釈を作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getFrame](#getFrame--) | caret 矩形を取得します。 |
| [getSymbol](#getSymbol--) | caret に関連付けられたシンボルを取得します。 {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | caret 矩形を設定します。 |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | インポート用の出力ページサイズを設定します。 |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Generator で使用するコンストラクタ。

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
指定されたページに新しい Caret 注釈を作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

caret 矩形を取得します。

**Returns:**
caret 矩形。

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

caret に関連付けられたシンボルを取得します。 {@code CaretSymbol}

**Returns:**
CaretSymbol 要素 @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
caret 矩形を設定します。

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
インポート用の出力ページサイズを設定します。
